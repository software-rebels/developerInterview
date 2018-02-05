
## Introduction

Thank you for joining this interview! 
The purpose of this interview is to understand how reviewing bots impact code review behaviors.
This page shows interview questions with our recent results.
We would like to discuss two themes as below:

### Theme 1: What are the perceived benefits of reviewing bots in code reviews?
```markdown
Q1-1: *What kinds of jobs in reviewing bots were used by Nova project?*
- pep8, tox-python, docs, functional job
- Tempest_dsvm_cells
- Tempest_dsvm_full_devstack_plugin_ceph
- Tempest−dsvm−neutron−multinode−ful
- Tempest−dsvm−multinode−live−migration
- Grenade_dsvm_neutron_multinode
- Tempest−dsvm−ipa−wholedisk−bios−agent

Q1-2: *Which jobs are necessary or optional to verify codes?*
-> We would like to know what jobs are needed to study
```
```markdown
Q2: *How do those jobs contribute to code reviews over time?*
- Our research shows that the coverage of a job (i.e., how much of past reviews are verified by the job) tends to decease once it becomes mature. For example, while pep8 job (1st plot) has arrived at almost 100% in early period, it has decreased to 85% in late period.
```
![activejobcoverageovertime](https://user-images.githubusercontent.com/12183635/35810142-b635c052-0a58-11e8-9de7-1806343bbbbf.jpg)

```markdown
Q3: *How do those jobs influence code reviews?*
 - quality (content, quality etc.)?
 - cost (time, #revision etc.)?
 - motivation (participation etc.)?
```

### Theme 2: Do those perceived benefits materialize in historical data?
```markdown
Q1: *What kinds of features show those perceived benefits?*
 - quality -> bug information?
 - cost -> review time or discussion length?
 - motivation -> The number of review participants?
```

```markdown
Q2: *What is the challenge (or expectation) of reviewing bots in the future?*
```

### Contact Information
[Toshiki Hirao](http://toshiki-hirao.jpn.org/)

hirao.toshiki.ho7@is.naist.jp
Nara Institute of Science and Technology, Nara, Japan

[Shane McIntosh](http://shanemcintosh.org/)

shane.mcintosh@mcgill.ca
McGill University, Québec, Canada

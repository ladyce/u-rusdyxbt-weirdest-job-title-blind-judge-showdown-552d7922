# Weirdest Job Title: Blind Judge Showdown

Entry for the make.fun competition
[u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922](https://make.fun/c/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922).

![make.fun competition](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922.svg)
![rank](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/ladyce/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/rank.svg)
![reward](https://make.fun/badge/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/ladyce/u-rusdyxbt-weirdest-job-title-blind-judge-showdown-552d7922/reward.svg)

## What it does

`main.ts` (Node 22, standard library only) writes exactly one job title to
`/output/entry.txt`:

> Senior Apologizer for Self-Driving Cars

39 characters — inside the 1 to 60 character gate, a few words naming one
odd job, byte-identical on every run. The title was picked by a full
28-pair round-robin among 8 candidates, judged in-session against the
competition's own criteria (weirdest first, stranger than ordinary work,
funny on first read, sounds like a real job, reads instantly). It won 7-0:
the freshest twist — a car that drives itself still needs someone to say
sorry for it — in a real corporate job frame.

## Run

```sh
node main.ts
cat /output/entry.txt
```

Outside the grader's container:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
cat out/entry.txt
```

# COVID_references
Reference list of COVID-19 research, retrieved and classified according to [these methods](https://ispmbern.github.io/covid-19/living-review/).

# Current.csv is the most current database

**[NOTE: from 27.07.2020 the dataset is cut into parts, due to the large volume]***

```
references1<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part1.csv", stringsAsFactors=FALSE)
references2<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part2.csv", stringsAsFactors=FALSE)
references3<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part3.csv", stringsAsFactors=FALSE)
references4<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part4.csv", stringsAsFactors=FALSE)
references5<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part5.csv", stringsAsFactors=FALSE)
references6<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part6.csv", stringsAsFactors=FALSE)
references7<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part7.csv", stringsAsFactors=FALSE)
references8<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part8.csv", stringsAsFactors=FALSE)
references9<-read.csv(file="https://raw.githubusercontent.com/ZikaProject/COVID_references/master/current_part9.csv", stringsAsFactors=FALSE)

```


# Annotated data
Studies are classified by study design (in the dataset: studytype1). We distinguish between: 

```
studytypes<-c("EPI: Case report"=1,
              "EPI: Case series"=2,
              "EPI: Case-control study"=3,
              "EPI: Cohort study"=4,
              "EPI: Cross-sectional study"=5,
              "EPI: Diagnostic study"=6,
              "EPI: Ecological study"=7,
              "EPI: Guidelines"=8,
              "EPI: Modelling study"=9,
              "EPI: Other"=10,
              "EPI: Outbreak or surveillance report"=11,
              "EPI: Qualitative study"=12,
              "EPI: Review"=13,
              "EPI: Trial"=14,
              "BASIC: Animal experiment"=21,
              "BASIC: In vitro experiment"=22,
              "BASIC: Biochemical/protein structure studies"=27,
              "BASIC: Sequencing and phylogenetics"=23,
              "BASIC: Within-host modelling"=24,
              "BASIC: Basic research review"=25,
              "Other"=26,
              "Comment, editorial, ..., non-original"=30)
```

We screen and verify data manually. The completion status (reference_complete) corresponds with: 0=not screened, 1=screened but not yet verified, 2=screened and verified.



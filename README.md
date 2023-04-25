# MySQL- 應徵職缺記錄資料庫

## Table of Contents

- [Background](#background)
- [Environment](#environment)
- [Original Dataset](#original-dataset)
- [Source Code](#source-code)
- [Result](#result)
- [Reference Source](#reference-source)

## Background
   最近進修結束開始投數據領域的工作，所以在mac notes隨手紀錄應徵過的工作。
因為要新增欄位，靈機一動將資料寫進MySQL資料庫並自學[Git做版本控制](https://github.com/reginamao/git)，作為履歷的作品集。

## Environment
MySQL

## Basic Functions

```
create database jobs;
```

```
$CREATE TABLE table_name (
    column_name1 data_type,
    column_name2 data_type,
    ...
)
```

```
SELECT * FROM table_name;
)
```

```
SELECT * FROM Job.application
WHERE Status is NOT NULL;
```
![ReginaMao](https://imgur.com/stukrgI.gif)

## Original Dataset
Before (Notes on Mac)

![ReginaMao](https://imgur.com/1743swr.png "jobs")

## Source Code
View more > [Job.application.sql](https://github.com/reginamao/jobs.application-mysql/blob/main/Jobs.application.sql)

## Result
![ReginaMao](https://imgur.com/v8il9Cs.gif)

## Reference Source
* [https://www.w3schools.com/MySQL/default.asp](https://www.w3schools.com/MySQL/default.asp)

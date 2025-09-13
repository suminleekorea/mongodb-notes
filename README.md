# MongoDB Notes

## 📖 Overview

This repository contains my notes and exercises on **MongoDB**, focusing on schema design, queries, and analytics-driven use cases.

## 🗂 Contents

* `notes/` → Markdown documentation of MongoDB concepts
* `examples/` → JSON documents and schema samples
* `queries/` → Example queries and aggregation pipelines

## 🔑 Key Topics

* Flexible schemas vs relational schemas
* **Reference Model** vs **Embedded Model**
* CRUD operations: `insertOne`, `find`, `updateOne`, `deleteOne`
* Operators: `$gt`, `$lt`, `$exists`, `$regex`, `$expr`
* Aggregation pipelines
* Case study: Customer–Order–Product schema design

## 🚀 Usage

```bash
# Start Mongo shell
mongosh

# Import JSON dataset
mongoimport --db testdb --collection tvshows --file tvshows.json

# Run queries from queries/examples.js
```

## 🎯 Goal

Develop practical skills in MongoDB schema modeling and querying for analytics and business applications.

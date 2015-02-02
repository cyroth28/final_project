# Schema Information

## doctors
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
name        | string    | not null

## patients
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
doctor_id   | ingeger   | not null, foreign key (references doctors)
name        | string    | not null
insurer     | string    | not null
address     | string    | not null

## exercises
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
title       | string    | not null
exercise url| string    | not null
reps        | integer   | not null
sets        | integer   | not null

## patient_exercises
column name | data type | details
------------|-----------|-----------------------
id          | integer   | not null, primary key
patient_id  | integer   | not null, foreign key (references patients)
exercise_id | integer   | not null, foreign key (references exercises)

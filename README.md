# SQL_MOCKUP_DATA
# Codecademy Learners Data Analysis</span>
This project involves analyzing mockup Codecademy learners data using SQL queries. The dataset consists of two tables: `users` and `progress`.

## Project Goals

The main objectives of this project are:

1. Analyze the dataset using SQL queries.
2. Extract insights regarding learner demographics, preferences, and behaviors.

## Dataset Description

The dataset includes the following tables:

1. `users` table:
   - `user_id`: Unique identifier for each user.
   - `email_domain`: Domain of the user's email address.
   - `country`: Country of the user.
   - `postal`: Postal code of the user's location.
   - `mobile_app`: Indicates whether the user is using the mobile app.
   - `sign_up_at`: Timestamp of user sign-up.

2. `progress` table:
   - `user_id`: Unique identifier for each user (foreign key).
   - `learn_cpp`: Indicates progress in learning C++.
   - `learn_sql`: Indicates progress in learning SQL.
   - `learn_html`: Indicates progress in learning HTML.
   - `learn_javascript`: Indicates progress in learning JavaScript.
   - `learn_java`: Indicates progress in learning Java.

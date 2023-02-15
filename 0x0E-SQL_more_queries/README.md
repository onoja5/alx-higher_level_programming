# SQL - More queries
This project was done during my Full Stack Software Engineering Course at ALX Africa. The learning objectives is to learn about
* How to create a new MySQL user
* How to manage privileges for a user to a database or table
* What’s a PRIMARY KEY
* What’s a FOREIGN KEY
* How to use NOT NULL and UNIQUE constraints
* How to retrieve datas from multiple tables in one request
* What are subqueries
* What are JOIN and UNION

## Technologies
* `MySQL 5
* Tested on Ubuntu 20.04 LTS

## Files

All the following files are scripts of MySQL:

| Filename | Description |
| -------- | ----------- |
| `0-privileges.sql` | This lists all privileges of the MySQL users `user_0d_1` and `user_0d_2` on your server. |
| `1-create_user.sql` | This creates the MySQL server user `user_0d_1` |
| `2-create_read_user.sql` | This creates the database `hbtn_0d_2` and the user `user_0d_2` |
| `3-force_name.sql` | This creates the table `force_name` on your MySQL server |
| `4-never_empty.sql` | This creates the table `id_not_null` on your MySQL serve |
| `5-unique_id.sql` | This creates the table `unique_id` on your MySQL server |
| `6-states.sql` | This creates the database `hbtn_0d_usa` and the table `states` (in the database `hbtn_0d_usa`) |
| `7-cities.sql` | This creates the database `hbtn_0d_usa` and the table `cities` (in the database `hbtn_0d_usa`) |
| `8-cities_of_california_subquery.sql` | This lists all the cities of California that can be found in the database `hbtn_0d_usa` |
| `9-cities_by_state_join.sql` | This lists all cities contained in the database `hbtn_0d_usa` |
| `10-genre_id_by_show.sql` | This lists all shows contained in `hbtn_0d_tvshows` that have at least one genre linked |
| `11-genre_id_all_shows.sql` | This lists all shows contained in the database `hbtn_0d_tvshows` |
| `12-no_genre.sql` | This lists all shows contained in `hbtn_0d_tvshows` without a genre linked |
| `13-count_shows_by_genre.sql` | This lists all genres from `hbtn_0d_tvshows` and displays the number of shows linked to each |
| `14-my_genres.sql` | This uses the `hbtn_0d_tvshows` database to lists all genres of the show `Dexter` |
| `15-comedy_only.sql` | This lists all Comedy shows in the database `hbtn_0d_tvshows` |
| `16-shows_by_genre.sql` | This lists all shows, and all genres linked to that show, from the database `hbtn_0d_tvshows` |
| `100-not_my_genres.sql` | This uses the `hbtn_0d_tvshows` database to list all genres not linked to the show `Dexter` |
| `101-not_a_comedy.sql` | This lists all shows without the genre `Comedy` in the database `hbtn_0d_tvshows` |
| `102-rating_shows.sql` | This lists all shows from `hbtn_0d_tvshows_rate` by their rating |
| `103-rating_genres.sql` | This lists all genres in the database `hbtn_0d_tvshows_rate` by their rating |

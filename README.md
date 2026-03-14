##Category_id##
| Attributen | Date Type | Desciption | Constraints |
|---|---|---|---|
|catory_id | serial | unique identifier of user | primary key|

##Theatert##
| Attributen | Date Type | Desciption | Constraints |
|---|---|---|---|
| theatert_id | serial | unique identifier of user | primary key|
| capacity | integer | ---------------------- | Not Null |

##Movie##
| Attributen | Date Type | Desciption | Constraints |
|---|---|---|---|
| movie_id | serial | unique identifier of user | primary key,Not Null|
| category | integer | ---------------------- | forange key ,Not Null |
| title  | vachar(255) |title of movie | Not Null |
| duration | integer(255) |----------------- | Not Null ]
| dub_language | varcha(255) |----------------- | Not Null ]
| sub_language | vacha(255) |----------------- | Not Null ]


##Customer##
| Attributen | Date Type | Desciption | Constraints |
|---|---|---|---|
| customer_id | vacha(255) |-------------| primary key, Not null |
| firsrname | vacha(255) |-------------| Not null |
| surename | vacha(255) |-------------| Not null |

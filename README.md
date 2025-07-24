WIP.
Kludged together a Kometa anime genre collections config that uses Plex builder for genres already in Plex, rather than via MAL builder.
This is used in conjuction with Romaji-Renamer https://github.com/Arial-Z/Romaji-Renamer
which pulls genres/tags from Anilist rather than MAL, and populates a metadata file that Kometa uses to update Plex.

Have tried to make a relatively like-for-like to match Anilist genres with MAL equivalent, and borrowing a lot from JJJonesJr33/Plex-Meta-Manager-Anime

Reason - Kometa MAL builder for genre collections is exceptionally slow. Kometa mass genre update for MAL only creates the basic 18 MAL genres, not the extended genres under Themes and Demographics.

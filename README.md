# Orvid films

Film repository for [Orvid](https://github.com/mankidev/orvid). It holds sources for full-length films with posters and subtitles: HDFilmCehennemi (Turkish) and LookMovie (English, subtitles in many languages).

To add it, open Filters → Repositories → Add repository in Orvid and paste:

```
https://raw.githubusercontent.com/mankidev/orvid-films/main/
```

Orvid also suggests it under Filters → Repositories once [orvid-sources](https://github.com/mankidev/orvid-sources) is added.

Adding the word "film" or "movie" to a search puts film results first.

The source format is described in [orvid-sources](https://github.com/mankidev/orvid-sources#source-format). `python3 tools/build.py` signs the index with the key in `ORVID_FILMS_KEY`.

## License

GPL-3.0-or-later.

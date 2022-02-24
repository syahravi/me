Life
====

It's a **timeline of important events**

So, this is it. Have a look at [syahravi.my.id/timeline](https://tl.syahravi.my.id).

Forked from [Cheeaun](https://github.com/cheeaun/life)

Features
--------

- Super simple
- No fancy formatting
- No fancy setup
- No fancy effects
- Flexible datetimes because sometimes you don't remember the exact date of an event

How to setup your own *Life*
----------------------------

1. Fork or Clone this project.
2. Make a copy of `life.example.md` and `config.example.json`, rename it to `life.md` and `config.json`.
3. Add your life events into `life.md`.
4. Preview it on a local server. Use [`python -m http.server`] for Python3.
5. Commit and push your project Life.
6. Update the website link in your GitHub repo description.
7. Tell the world about your Life.
8. Add your Life to the [Lives](https://github.com/cheeaun/life/wiki/Lives) page.

How to configure your *Life*
----------------------------

The configuration:

- `customStylesheetURL` - (*string*, default to `null`) Path to a custom stylesheet file, for those who doesn't like the default *theme*.
- `yearLength` - (*number*, default to `120`) The width of the year grids, in pixels.
- `hideAge` - (*boolean*, default to `false`) Option to hide age from year axis.

Datetime "syntax"
-----------------

- `2000` - event that happen in that year
- `01/2000` - event that happen in that month/year
- `01/01/2000` - event that happen exactly in that day/month/year
- `2001-2005`, `10/2001-02/03/2005` - event that happen within the two dates
- `~2005` - event that happen around the time in that year
- `2005-~` - event that happen from that year and beyond (now).

Other people's Lives
--------------------

Here's [a compilation of Lives from the people who have forked Life](https://github.com/cheeaun/life/wiki/Lives).

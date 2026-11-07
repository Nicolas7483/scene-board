# Borderlands Scene Board

TV ambience for the table: full screen YouTube visuals with separate music and ambience, switched by one cell in a Google Sheet.

- TV: https://nicolas7483.github.io/scene-board/ (open on the TV, press Start session)
- Phone remote: https://claude.ai/artifact/Hq6JFJxEWM5uKzUP5VDSgT#remote
- Control sheet: https://docs.google.com/spreadsheets/d/1oCoPLPpskk381FjGds7VneR6OUfrT8oGSwpkpHK9EN0/edit (must be shared as Anyone with the link, Viewer)

Sheet row 1: A1 scene, B1 music volume 0 to 100, C1 ambience volume 0 to 100, D1 muted TRUE or FALSE.
Scenes: road_day, forest, night_camp, town_inn, underground, ruins, storm, tension, combat, boss_fight, victory_rest.

Each scene lists three YouTube candidates per layer (PICKS in index.html). If a video will not play, the next one is used;
if all fail, the page plays its own synthesized sound or painted visuals so the TV is never silent.

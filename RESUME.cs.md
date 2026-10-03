---
schema_version: 7
type: sample
file_count: 245
avg_lines_per_file: 108
move_to_legacy_percent: 10
generated_date: 2026-10-01
generated_time: 16:40:31
github_source_url: https://github.com/commandlineparser/commandline
last_build_ok: no
last_build_date: 2026-10-02
last_tests_run_date: n/a
covered_lines: n/a
total_lines: 21298
---

## Description

Fork knihovny CommandLineParser (Command Line Parser Library for CLR and NetStandard) pro zpracování argumentů příkazové řádky a nápovědy. Obsahuje zdroje v `src/CommandLine`, testy, ukázky (C# i VB) a stav odpovídá `CommandLineParserFw` na základě v2.9.0-preview1 s vlastními úpravami.

## Původ zdrojáků

Staženo z GitHubu: **ano** — [commandlineparser/commandline](https://github.com/commandlineparser/commandline)

- Zdroj určen podle: `gh api repos/sunamo/commandline` vrací `fork: true`, `parent: commandlineparser/commandline`; historie 1889 commitů od desítek cizích autorů (Giacomo Stelluti Scala, Eric Newton, ...); shoda git hashe 67 z 205 souborů `.cs/.vb/.md/.snk/.sln` s upstreamem (např. `CommandLine.snk`, `License.md`, `README.md`, `CHANGELOG.md`); README a licence jsou od původních autorů.

## Doporučení přesunu do legacy

Doporučení přesunu do sunamocz-legacy.visualstudio.com: **10 %** — fork oblíbené open source knihovny, nepřesouvat kvůli vlastním úpravám a zachování historie.

- Zachovává celou historii (1889 commitů) a licenci upstreamu.
- Vlastní část jsou úpravy snímku `CommandLineParserFw` (4 commity), které by po smazání zanikly.
- Knihovna je aktivně používaná (balíček `CommandLineParser` na NuGetu).

## Vazby na moje repa

- Submoduly: žádné
- ProjectReference / PackageReference: žádné

---
schema_version: 11
type: forked-notmine-library
category_override: none
file_count: 245
file_extensions: cs:189, md:6, png:6, vb:6, config:5, noext:5, csproj:4, fsx:4, slnx:4, resx:3, cshtml:1, json:1, manifest:1, myapp:1, pdn:1, props:1, settings:1, snk:1, svclog:1, user:1, vbproj:1, xml:1, yml:1
file_extensions_updated: 2026-10-04
avg_lines_per_file: 108
total_lines: 21298
metrics_lm: 2026-10-01 16:40:31
move_to_legacy_percent: 10
description_updated: 2026-10-01
links_updated: 2026-10-01
github_source_url: https://github.com/commandlineparser/commandline
origin_status: found
origin_checked: 2026-10-01
article_source_url: not run
article_status: pending
article_checked: not run
last_build_ok: no
last_build_date: 2026-10-02
last_tests_run_date: not run
covered_lines: not run
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

source "https://rubygems.org"

gem "metanorma-cli"

# gem "metanorma-taste", github: "metanorma/metanorma-taste", branch: "main"
# gem "metanorma-ribose", github: "metanorma/metanorma-ribose"
# gem "metanorma-standoc", github: "metanorma/metanorma-standoc"
# gem "sassc-embedded"
gem "relaton", "~> 3.1.1"
# metanorma 2.5.14+ requires Relaton::Render::Unrenderable, which the
# released relaton-render (3.0.0) does not define — isodoc#882/#883
# broke the same way. Ride git main until a 3.1.x release cuts.
gem "relaton-render", github: "relaton/relaton-render", branch: "main"
gem "pubid", "~> 2.0" # 2.0.0 released; the git source now carries the 2.1 pre line
gem "moxml", github: "lutaml/moxml", branch: "main"

# -*- mode:ruby -*-
require 'rake'

desc "building document with sphinx"
task :docs do
  build_dir = "docs/_build"
  `LC_CTYPE=C sphinx-build -b html -d #{build_dir}/doctrees -D latex_paper_size=a4 docs #{build_dir}/html`
end

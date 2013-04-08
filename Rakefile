task :build do
  `mdpress -a deck.md -s pivotal`
end

task :open do
  `open deck/index.html`
end

task :default => [:build, :open]

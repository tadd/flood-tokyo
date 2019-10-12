task default: 'public/index.html'

file 'public/index.html' => 'README.md' do |t|
  sh "pandoc -s -Mtitle=東京水害対策情報 -f gfm+east_asian_line_breaks #{t.source} -o #{t.name}"
end

guard 'bundler' do
  watch('Gemfile')
  watch('omniauth-docusign.gemspec')
end

guard :rubocop do
  watch(%r{.+\.rb$})
  watch(%r{(?:.+/)?\.rubocop\.yml$}) { |m| File.dirname(m[0]) }
end

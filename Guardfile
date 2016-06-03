# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'livereload', :port => '35729', :host => '127.0.0.1' do
  watch(%r{.+\.(html)})
  watch(%r{stylesheets/.+\.(css)})
  watch(%r{scripts/.+\.(js)})
end

guard :compass

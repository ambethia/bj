task :foobar do
  puts 42
end

begin
  require 'jeweler'
  Jeweler::Tasks.new do |spec|
    spec.name = 'bj'
    spec.summary = "Backgroundjob (Bj) is a brain dead simple, zero admin, background priority queue for Rails."
    spec.description = "Backgroundjob (Bj) is a brain dead simple, zero admin, background priority queue for Rails."
    spec.add_dependency 'main', '>= 2.6.0'
    spec.add_dependency 'systemu', '>= 1.2.0'
    spec.add_dependency 'orderedhash', '>= 0.0.3'
    spec.author = "Ara T. Howard"
    spec.email = "ara.t.howard@gmail.com"
    spec.files.reject! { |fn| fn.include? ".git" }
  end
rescue LoadError
  puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end
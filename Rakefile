load "middleman-gh-pages/tasks/gh-pages.rake"

task :copy_cname do
  system("cp CNAME build") || exit(1)
end

# Adds copy_cname as a prerequisite of the existing publish task
task :publish => :copy_cname

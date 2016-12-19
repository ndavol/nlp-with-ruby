namespace :test do
  task :links do
    require 'awesome_bot'
    content = File.read('README.md')
    result = AwesomeBot.check(content)
    puts result.success(nil) ? ':)' : ':('
  end
end

task :toc do
  `node_modules/markdown-toc/cli.js -i README.md`
end

SSH = 'ssh -A -i /home/ubuntu/.ssh/id_rsa.pub -l ubuntu'

desc "Run Puppet on ENV['CLIENT']"
task :apply do
  client = ENV['CLIENT']
  sh "git push"
  sh "#{SSH} #{client} pull-updates"
end

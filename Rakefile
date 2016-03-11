<<<<<<< HEAD
SSH = 'ssh -A -i /home/ubuntu/.ssh/id_ra.pub -l ubuntu'
=======
SSH = 'ssh -A -i /home/ubuntu/.ssh/id_rsa.pub -l ubuntu'
>>>>>>> d4c6b932eeb1e25c82f5e98570af55f1e57379e1

desc "Run Puppet on ENV['CLIENT']"
task :apply do
  client = ENV['CLIENT']
  sh "git push"
  sh "#{SSH} #{client} pull-updates"
end

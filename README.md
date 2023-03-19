
# rkazi-actions


test-ruby-tool-1 : v0.1.0 (latest version)
[x] - test-ruby-tool-1:  dependency 'test-ruby-tool-2' [~> 0.0.1](latest: )
[+] - test-ruby-tool-1: Development dependency 'bundler' [= 1.16]
[x] - test-ruby-tool-1: Development dependency 'rake' [~> 12.3]
[+] - test-ruby-tool-1: Development dependency 'rspec' [= 3.8]
[x] - test-ruby-tool-1: Development dependency 'rubocop' [~> 0.59.2]
[x] - test-ruby-tool-1: Runtime dependency 'tool-3' [~> 0.0.1]
[+] - test-ruby-tool-1: Runtime dependency 'tool-4' [= 0.0.1]
--------------------------------------------

test-ruby-tool-2 : v0.1.0 (latest version)
[+] - test-ruby-tool-2:  dependency 'test-ruby-tool-1' [0.0.1](latest: )
[+] - test-ruby-tool-2: Development dependency 'bundler' [= 1.16]
[x] - test-ruby-tool-2: Development dependency 'rake' [~> 12.3]
[+] - test-ruby-tool-2: Development dependency 'rspec' [= 3.8]
[x] - test-ruby-tool-2: Development dependency 'rubocop' [~> 0.59.2]
[x] - test-ruby-tool-2: Runtime dependency 'tool-3' [~> 0.0.1]
[+] - test-ruby-tool-2: Runtime dependency 'tool-4' [= 0.0.1]
--------------------------------------------


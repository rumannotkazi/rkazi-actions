
# rkazi-actions


test-ruby-tool-1 : v0.1.0 (latest version)

[x] -  dependency 'test-ruby-tool-2' [~> v0.0.1] (latest: vv0.1.0)

[+] - Development dependency 'bundler' [= v1.16]

[x] - Development dependency 'rake' [~> v12.3]

[+] - Development dependency 'rspec' [= v3.8]

[x] - Development dependency 'rubocop' [~> v0.59.2]

[x] - Runtime dependency 'tool-3' [~> v0.0.1]

[+] - Runtime dependency 'tool-4' [= v0.0.1]

--------------------------------------------

test-ruby-tool-2 : v0.1.0 (latest version)

[+] -  dependency 'test-ruby-tool-1' [= v0.0.1] (latest: vv0.1.0)

[+] - Development dependency 'bundler' [= v1.16]

[x] - Development dependency 'rake' [~> v12.3]

[+] - Development dependency 'rspec' [= v3.8]

[x] - Development dependency 'rubocop' [~> v0.59.2]

[x] - Runtime dependency 'tool-3' [~> v0.0.1]

[+] - Runtime dependency 'tool-4' [= v0.0.1]

--------------------------------------------


# devops-a1-part1

DevOps Assignment 1 Part 1

# Command - docker build -t devops-a1-part1 .

# Output

=> [internal] load .dockerignore 0.0s

=> => transferring context: 2B 0.0s

=> [internal] load build definition from Dockerfile 0.0s

=> => transferring dockerfile: 247B 0.0s

=> [internal] load metadata for docker.io/library/php:8.1-apache 11.7s

=> [1/3] FROM docker.io/library/php:8.1-apache@sha256:df542e57145a5272a3b374199e03a839dfa1843d3c93e42ea7b10c3a213749fd 42.6s

=> => resolve docker.io/library/php:8.1-apache@sha256:df542e57145a5272a3b374199e03a839dfa1843d3c93e42ea7b10c3a213749fd 0.0s

=> => sha256:effaa4d9186a8be1aed5f2ccec0e161d7d36842300333a93d56d603b47df58e5 3.04kB / 3.04kB 0.0s

=> => sha256:df542e57145a5272a3b374199e03a839dfa1843d3c93e42ea7b10c3a213749fd 1.86kB / 1.86kB 0.0s

=> => sha256:a0a360b2e4881d2b031e9e39a21110ab55a580676fcd59d68227dd7557fe35e2 12.73kB / 12.73kB 0.0s

=> => sha256:381c9f838d23f8118bfd5cbaf969e6781ce721288fdbf4811d4613b8c94a0acb 98.13MB / 98.13MB 39.0s

=> => sha256:31ce7ceb6d443e2ab4ae91695fea10e1443417fd94c40a46994d5a96940ea1ca 29.18MB / 29.18MB 13.9s

=> => sha256:74a1d4347681dafacc4fd7807e0fd4250100fd23d88a3a5bb93ba9de6ebfa853 228B / 228B 1.2s

=> => sha256:acb23c56d5c248ab07de2c65e6805408398ad24b9e7f68b76a772fd923a541f0 270B / 270B 1.7s

=> => sha256:59d3602892ec55ef6fa41b79e63f381805cacfdd794280d67a0b4babd0bec43b 20.31MB / 20.31MB 38.7s

=> => extracting sha256:31ce7ceb6d443e2ab4ae91695fea10e1443417fd94c40a46994d5a96940ea1ca 1.2s

=> => sha256:339958c8b19db06ee2019751c64cb419ac60d5e696023999e381ac3d84a8511f 476B / 476B 14.4s

=> => sha256:663bea60fafb0c6c43b3bf486910e7685edaa95e7b4794a8b5f952cc546ca561 512B / 512B 14.9s

=> => sha256:24fd3bc3cf2c30ed1cf840853c3c4def1f65052fc214234daac7ec82a3305631 12.22MB / 12.22MB 23.6s

=> => extracting sha256:74a1d4347681dafacc4fd7807e0fd4250100fd23d88a3a5bb93ba9de6ebfa853 0.0s

=> => sha256:0c76b281efbbce580fa2d78d9bb8405d9c4ce03b63b56eabb3c53e67a621f7b5 492B / 492B 24.9s

=> => sha256:89d42d23c585dbd3d5b6f8128374b23ea02d9ea7150f8b10e0639b4a98ba141e 11.15MB / 11.15MB 33.0s

=> => sha256:de946440e878c565797c75a4ef1451eca4737aa7c6894f9cd4c1117707b30605 2.46kB / 2.46kB 34.1s

=> => sha256:b8e2dc25626e374568cdcd5d4e790d5e6b8547e805d677f5cff590509cf22ed5 246B / 246B 34.6s

=> => sha256:8f5b834c006ad3f01146dbc2c40786c38e3df7f2870c29f053782e1ff1f6b233 895B / 895B 36.0s

=> => extracting sha256:381c9f838d23f8118bfd5cbaf969e6781ce721288fdbf4811d4613b8c94a0acb 2.5s

=> => extracting sha256:acb23c56d5c248ab07de2c65e6805408398ad24b9e7f68b76a772fd923a541f0 0.0s

=> => extracting sha256:59d3602892ec55ef6fa41b79e63f381805cacfdd794280d67a0b4babd0bec43b 0.4s

=> => extracting sha256:339958c8b19db06ee2019751c64cb419ac60d5e696023999e381ac3d84a8511f 0.0s

=> => extracting sha256:663bea60fafb0c6c43b3bf486910e7685edaa95e7b4794a8b5f952cc546ca561 0.0s

=> => extracting sha256:24fd3bc3cf2c30ed1cf840853c3c4def1f65052fc214234daac7ec82a3305631 0.1s

=> => extracting sha256:0c76b281efbbce580fa2d78d9bb8405d9c4ce03b63b56eabb3c53e67a621f7b5 0.0s

=> => extracting sha256:89d42d23c585dbd3d5b6f8128374b23ea02d9ea7150f8b10e0639b4a98ba141e 0.3s

=> => extracting sha256:de946440e878c565797c75a4ef1451eca4737aa7c6894f9cd4c1117707b30605 0.0s

=> => extracting sha256:b8e2dc25626e374568cdcd5d4e790d5e6b8547e805d677f5cff590509cf22ed5 0.0s

=> => extracting sha256:8f5b834c006ad3f01146dbc2c40786c38e3df7f2870c29f053782e1ff1f6b233 0.0s
=> [internal] load build context 0.0s

=> => transferring context: 4.17kB 0.0s

=> [2/3] WORKDIR /var/www/html 0.6s

=> [3/3] COPY . /var/www/html 0.0s

=> exporting to image 0.0s

=> => exporting layers 0.0s

=> => writing image sha256:324b1054b500c582dc972b6aaece579915cec26adf850ae82ff3c70d4094cd04 0.0s

=> => naming to docker.io/library/devlops-a1-part1

# Command - docker run -p 8090:80 devops-a1-part1

# Output

AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.17.0.2. Set the 'ServerName' directive globally to suppress this message

AH00558: apache2: Could not reliably determine the server's fully qualified domain name, using 172.17.0.2. Set the 'ServerName' directive globally to suppress this message

[Fri Nov 03 16:36:17.188478 2023] [mpm_prefork:notice] [pid 1] AH00163: Apache/2.4.57 (Debian) PHP/8.1.25 configured -- resuming normal operations

[Fri Nov 03 16:36:17.188513 2023] [core:notice] [pid 1] AH00094: Command line: 'apache2 -D FOREGROUND'

192.168.65.1 - - [03/Nov/2023:16:36:29 +0000] "GET / HTTP/1.1" 200 253 "-" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:109.0) Gecko/20100101 Firefox/119.0"

192.168.65.1 - - [03/Nov/2023:16:36:29 +0000] "GET /favicon.ico HTTP/1.1" 404 489 "http://localhost:8090/" "Mozilla/5.0 (Macintosh; Intel Mac OS X 10.15; rv:109.0) Gecko/20100101 Firefox/119.0"

# Command - docker images

REPOSITORY TAG IMAGE ID CREATED SIZE

devlops-a1-part1 latest 22a7f5f87c6b 5 minutes ago 512MB

# Command - Docker Login

# Output

- Authenticating with existing credentials...

- Login Succeeded

# command - docker tag devlops-a1-part1 faisalabbasm/devlops-a1-part1

No Output

# command - docker push faisalabbasm/devlops-a1-part1

# output

Using default tag: latest

The push refers to repository [docker.io/faisalabbasm/devlops-a1-part1]

e0d40fded302: Pushed

5f70bf18a086: Pushed

d0e144034b78: Mounted from library/php

33e0a1d9eab6: Mounted from library/php

37bd6ca6b853: Mounted from library/php

80c5f780bc18: Mounted from library/php

26f9fa485a90: Mounted from library/php

c86e764174ae: Mounted from library/php

bd89adcfe362: Mounted from library/php

f5e8beef5458: Mounted from library/php

bc1183b17a03: Mounted from library/php

718a61de0a68: Mounted from library/php

b865244640eb: Mounted from library/php

e4639fd40155: Mounted from library/php

70e628269d9f: Mounted from library/php

latest: digest: sha256:6f92723ea30d65aef620b06d74b1b6d0af08ce79389fdbc87e40126d7cc2045d size: 3450

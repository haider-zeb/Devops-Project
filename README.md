C:\\Users\\HP\\Desktop\\dockerProject\\client\>docker-compose build
\[+\] Building 4.6s (15/15) FINISHED docker:default =\> \[server
internal\] load .dockerignore 0.0s =\> =\> transferring context: 2B 0.0s
=\> \[server internal\] load build definition from dockerfile 0.0s =\>
=\> transferring dockerfile: 109B 0.0s =\> \[client internal\] load
metadata for docker.io/library/python:3.7-alpine 4.2s =\> \[server
internal\] load build context 0.0s =\> =\> transferring context: 31B
0.0s =\> \[client 1/4\] FROM
docker.io/library/python:3.7-alpine@sha256:f3d31c8677d03f0b3c724446077f229a6ce9d3ac430f5c08
0.0s =\> CACHED \[server 2/3\] ADD server.py /server/ 0.0s =\> CACHED
\[server 3/3\] WORKDIR /server/ 0.0s =\> \[server\] exporting to image
0.0s =\> =\> exporting layers 0.0s =\> =\> writing image
sha256:fedf11e6e645233aeb93ab9bc32f405f8870b379419d8bb957bc64bfcd43d4f3
0.0s =\> =\> naming to docker.io/library/dockerproject-server 0.0s =\>
\[client internal\] load .dockerignore 0.0s =\> =\> transferring
context: 2B 0.0s =\> \[client internal\] load build definition from
dockerfile 0.0s =\> =\> transferring dockerfile: 136B 0.0s =\> \[client
internal\] load build context 0.0s =\> =\> transferring context: 91B
0.0s =\> CACHED \[client 2/4\] ADD client.py /client/ 0.0s =\> \[client
3/4\] ADD data.txt /client/ 0.0s =\> \[client 4/4\] WORKDIR /client/
0.0s =\> \[client\] exporting to image 0.1s =\> =\> exporting layers
0.0s =\> =\> writing image
sha256:557a74f3ac175d6463bb1b6c4b6ab8d632891801aa82a2606b7353c91166c89a
0.0s =\> =\> naming to docker.io/library/dockerproject-client

C:\\Users\\HP\\Desktop\\dockerProject\\client\>docker-compose up \[+\]
Building 0.0s (0/0) docker:default \[+\] Running 3/2 ✔ Network
dockerproject_default Created 0.0s ✔ Container dockerproject-server-1
Created 0.0s ✔ Container dockerproject-client-1 Created 0.1s Attaching
to dockerproject-client-1, dockerproject-server-1 dockerproject-client-1
\| \[SERVER\]: Filename received.

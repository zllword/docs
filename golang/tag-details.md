<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `golang`

-	[`golang:1.5.4`](#golang154)
-	[`golang:1.5`](#golang15)
-	[`golang:1.5.4-onbuild`](#golang154-onbuild)
-	[`golang:1.5-onbuild`](#golang15-onbuild)
-	[`golang:1.5.4-wheezy`](#golang154-wheezy)
-	[`golang:1.5-wheezy`](#golang15-wheezy)
-	[`golang:1.5.4-alpine`](#golang154-alpine)
-	[`golang:1.5-alpine`](#golang15-alpine)
-	[`golang:1.6.3`](#golang163)
-	[`golang:1.6`](#golang16)
-	[`golang:1`](#golang1)
-	[`golang:latest`](#golanglatest)
-	[`golang:1.6.3-onbuild`](#golang163-onbuild)
-	[`golang:1.6-onbuild`](#golang16-onbuild)
-	[`golang:1-onbuild`](#golang1-onbuild)
-	[`golang:onbuild`](#golangonbuild)
-	[`golang:1.6.3-wheezy`](#golang163-wheezy)
-	[`golang:1.6-wheezy`](#golang16-wheezy)
-	[`golang:1-wheezy`](#golang1-wheezy)
-	[`golang:wheezy`](#golangwheezy)
-	[`golang:1.6.3-alpine`](#golang163-alpine)
-	[`golang:1.6-alpine`](#golang16-alpine)
-	[`golang:1-alpine`](#golang1-alpine)
-	[`golang:alpine`](#golangalpine)
-	[`golang:1.7rc2`](#golang17rc2)
-	[`golang:1.7`](#golang17)
-	[`golang:1.7rc2-onbuild`](#golang17rc2-onbuild)
-	[`golang:1.7-onbuild`](#golang17-onbuild)
-	[`golang:1.7rc2-wheezy`](#golang17rc2-wheezy)
-	[`golang:1.7-wheezy`](#golang17-wheezy)
-	[`golang:1.7rc2-alpine`](#golang17rc2-alpine)
-	[`golang:1.7-alpine`](#golang17-alpine)

## `golang:1.5.4`

```console
$ docker pull golang@sha256:48499348e858bdd2441f0619f8814fee233d649e8ec2cf57e486bc32fe7f1c4c
```

-	Platforms:
	-	linux; amd64

### `golang:1.5.4` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **249.5 MB (249533351 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c3d2a6307f4e067587306908419b6e5aa476cc89165791fca64b3a658db4a7bd`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:23 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:23 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:24 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:25 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:25 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:28 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:3f69a6fde99ea8c3c23ac09ed064374364c23c393c1953207d25782a30168d20`  
		Last Modified: Fri, 17 Jun 2016 16:50:41 GMT  
		Size: 80.2 MB (80184820 bytes)
	-	`sha256:109455198000841897e869f8a4a576d7ba9f84a614e8684657ba919767b4b540`  
		Last Modified: Fri, 17 Jun 2016 16:50:10 GMT  
		Size: 122.0 B
	-	`sha256:a7fb14d9347a66a95e66e5b5b20e0fc7182a8b489b8dca75497c018fdab5d70e`  
		Last Modified: Tue, 28 Jun 2016 22:45:52 GMT  
		Size: 1.4 KB (1352 bytes)

## `golang:1.5`

```console
$ docker pull golang@sha256:48499348e858bdd2441f0619f8814fee233d649e8ec2cf57e486bc32fe7f1c4c
```

-	Platforms:
	-	linux; amd64

### `golang:1.5` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **249.5 MB (249533351 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:c3d2a6307f4e067587306908419b6e5aa476cc89165791fca64b3a658db4a7bd`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:23 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:23 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:24 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:25 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:25 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:28 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:3f69a6fde99ea8c3c23ac09ed064374364c23c393c1953207d25782a30168d20`  
		Last Modified: Fri, 17 Jun 2016 16:50:41 GMT  
		Size: 80.2 MB (80184820 bytes)
	-	`sha256:109455198000841897e869f8a4a576d7ba9f84a614e8684657ba919767b4b540`  
		Last Modified: Fri, 17 Jun 2016 16:50:10 GMT  
		Size: 122.0 B
	-	`sha256:a7fb14d9347a66a95e66e5b5b20e0fc7182a8b489b8dca75497c018fdab5d70e`  
		Last Modified: Tue, 28 Jun 2016 22:45:52 GMT  
		Size: 1.4 KB (1352 bytes)

## `golang:1.5.4-onbuild`

```console
$ docker pull golang@sha256:51af7b3af76b1047108a775126045f16c31a252b84dbeeb5eb6851af6f08573d
```

-	Platforms:
	-	linux; amd64

### `golang:1.5.4-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **249.5 MB (249533482 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:e5423bf96e516738327ce29f1b3646261cb7c152f77d764cb9cf3753746ab379`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:23 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:23 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:24 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:25 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:25 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:28 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Tue, 28 Jun 2016 22:45:30 GMT
RUN mkdir -p /go/src/app
# Tue, 28 Jun 2016 22:45:30 GMT
WORKDIR /go/src/app
# Tue, 28 Jun 2016 22:45:30 GMT
CMD ["go-wrapper" "run"]
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD COPY . /go/src/app
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD RUN go-wrapper download
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:3f69a6fde99ea8c3c23ac09ed064374364c23c393c1953207d25782a30168d20`  
		Last Modified: Fri, 17 Jun 2016 16:50:41 GMT  
		Size: 80.2 MB (80184820 bytes)
	-	`sha256:109455198000841897e869f8a4a576d7ba9f84a614e8684657ba919767b4b540`  
		Last Modified: Fri, 17 Jun 2016 16:50:10 GMT  
		Size: 122.0 B
	-	`sha256:a7fb14d9347a66a95e66e5b5b20e0fc7182a8b489b8dca75497c018fdab5d70e`  
		Last Modified: Tue, 28 Jun 2016 22:45:52 GMT  
		Size: 1.4 KB (1352 bytes)
	-	`sha256:253c72c9db50526c5bd18691b223f20089da3a91401212e5f04ba9b275f94d1b`  
		Last Modified: Tue, 28 Jun 2016 22:46:12 GMT  
		Size: 131.0 B

## `golang:1.5-onbuild`

```console
$ docker pull golang@sha256:51af7b3af76b1047108a775126045f16c31a252b84dbeeb5eb6851af6f08573d
```

-	Platforms:
	-	linux; amd64

### `golang:1.5-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **249.5 MB (249533482 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:e5423bf96e516738327ce29f1b3646261cb7c152f77d764cb9cf3753746ab379`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:12 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:23 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:23 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:24 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:25 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:25 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:28 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Tue, 28 Jun 2016 22:45:30 GMT
RUN mkdir -p /go/src/app
# Tue, 28 Jun 2016 22:45:30 GMT
WORKDIR /go/src/app
# Tue, 28 Jun 2016 22:45:30 GMT
CMD ["go-wrapper" "run"]
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD COPY . /go/src/app
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD RUN go-wrapper download
# Tue, 28 Jun 2016 22:45:31 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:3f69a6fde99ea8c3c23ac09ed064374364c23c393c1953207d25782a30168d20`  
		Last Modified: Fri, 17 Jun 2016 16:50:41 GMT  
		Size: 80.2 MB (80184820 bytes)
	-	`sha256:109455198000841897e869f8a4a576d7ba9f84a614e8684657ba919767b4b540`  
		Last Modified: Fri, 17 Jun 2016 16:50:10 GMT  
		Size: 122.0 B
	-	`sha256:a7fb14d9347a66a95e66e5b5b20e0fc7182a8b489b8dca75497c018fdab5d70e`  
		Last Modified: Tue, 28 Jun 2016 22:45:52 GMT  
		Size: 1.4 KB (1352 bytes)
	-	`sha256:253c72c9db50526c5bd18691b223f20089da3a91401212e5f04ba9b275f94d1b`  
		Last Modified: Tue, 28 Jun 2016 22:46:12 GMT  
		Size: 131.0 B

## `golang:1.5.4-wheezy`

```console
$ docker pull golang@sha256:0ec927183388ab6ea182231fb26b560b61a353bdca744b998a004449d2e4436a
```

-	Platforms:
	-	linux; amd64

### `golang:1.5.4-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **195.5 MB (195507452 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1526df7fc40c6522ae0d2075038bfd15faec2b2a0759f8689457fdcb4019e2a8`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:43 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:44 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:54 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:54 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:54 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:55 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:56 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:32 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6097098a0d1d67e2df33a6002ca50c4bb8690eb38287f9cb5ec6f92d07464262`  
		Last Modified: Fri, 17 Jun 2016 16:51:41 GMT  
		Size: 80.2 MB (80184792 bytes)
	-	`sha256:dcbab28a351e7afca9df76bab17b4be30e7dfc42b3100703c36160ca657d8a10`  
		Last Modified: Fri, 17 Jun 2016 16:51:11 GMT  
		Size: 122.0 B
	-	`sha256:0276a52f575f544144667c40c9404c4ca5f4c6a8d3faccbed3bb1a2c507af5a4`  
		Last Modified: Tue, 28 Jun 2016 22:46:33 GMT  
		Size: 1.4 KB (1352 bytes)

## `golang:1.5-wheezy`

```console
$ docker pull golang@sha256:0ec927183388ab6ea182231fb26b560b61a353bdca744b998a004449d2e4436a
```

-	Platforms:
	-	linux; amd64

### `golang:1.5-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **195.5 MB (195507452 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:1526df7fc40c6522ae0d2075038bfd15faec2b2a0759f8689457fdcb4019e2a8`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 10 Jun 2016 21:36:43 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.5.4.linux-amd64.tar.gz
# Fri, 10 Jun 2016 21:36:44 GMT
ENV GOLANG_DOWNLOAD_SHA256=a3358721210787dc1e06f5ea1460ae0564f22a0fbd91be9dcd947fb1d19b9560
# Fri, 10 Jun 2016 21:36:54 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Fri, 10 Jun 2016 21:36:54 GMT
ENV GOPATH=/go
# Fri, 10 Jun 2016 21:36:54 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 10 Jun 2016 21:36:55 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 10 Jun 2016 21:36:56 GMT
WORKDIR /go
# Tue, 28 Jun 2016 22:45:32 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6097098a0d1d67e2df33a6002ca50c4bb8690eb38287f9cb5ec6f92d07464262`  
		Last Modified: Fri, 17 Jun 2016 16:51:41 GMT  
		Size: 80.2 MB (80184792 bytes)
	-	`sha256:dcbab28a351e7afca9df76bab17b4be30e7dfc42b3100703c36160ca657d8a10`  
		Last Modified: Fri, 17 Jun 2016 16:51:11 GMT  
		Size: 122.0 B
	-	`sha256:0276a52f575f544144667c40c9404c4ca5f4c6a8d3faccbed3bb1a2c507af5a4`  
		Last Modified: Tue, 28 Jun 2016 22:46:33 GMT  
		Size: 1.4 KB (1352 bytes)

## `golang:1.5.4-alpine`

```console
$ docker pull golang@sha256:db4f9b160452858933cb982149396a2a27407cc81c00b3f77acb41dd7b57c50e
```

-	Platforms:
	-	linux; amd64

### `golang:1.5.4-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **68.3 MB (68279903 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7dda058f699072abc51878969d0accf1584006345d472daa3f0305d334fa03e0`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Fri, 01 Jul 2016 19:29:12 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 01 Jul 2016 19:29:13 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.4.src.tar.gz
# Fri, 01 Jul 2016 19:29:13 GMT
ENV GOLANG_SRC_SHA256=002acabce7ddc140d0d55891f9d4fcfbdd806b9332fb8b110c91bc91afb0bc93
# Fri, 01 Jul 2016 19:30:28 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& ./make.bash 		&& apk del .build-deps
# Fri, 01 Jul 2016 19:30:29 GMT
ENV GOPATH=/go
# Fri, 01 Jul 2016 19:30:30 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 01 Jul 2016 19:30:31 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 01 Jul 2016 19:30:32 GMT
WORKDIR /go
# Fri, 01 Jul 2016 19:30:33 GMT
COPY file:ce084cb461a5ff8443f1781f7b0af0a33ad2bd4fe7ca14df213f58fa79e0172b in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:189cf28ebbc5aee712ba9194f6308065957dcaff75ffd6fd1a66ebcfc3a0c9da`  
		Last Modified: Fri, 01 Jul 2016 19:34:34 GMT  
		Size: 65.6 MB (65624223 bytes)
	-	`sha256:11843d4b6571391fafc5bc609948e2b607d974a803127d39078522b990777af3`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 122.0 B
	-	`sha256:c1d9d7c9cb3e4bfbd999a501cf1746f7e3eba20f13544a38dff7c8c274711cfe`  
		Last Modified: Fri, 01 Jul 2016 19:34:12 GMT  
		Size: 1.3 KB (1348 bytes)

## `golang:1.5-alpine`

```console
$ docker pull golang@sha256:db4f9b160452858933cb982149396a2a27407cc81c00b3f77acb41dd7b57c50e
```

-	Platforms:
	-	linux; amd64

### `golang:1.5-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **68.3 MB (68279903 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7dda058f699072abc51878969d0accf1584006345d472daa3f0305d334fa03e0`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Fri, 01 Jul 2016 19:29:12 GMT
ENV GOLANG_VERSION=1.5.4
# Fri, 01 Jul 2016 19:29:13 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.5.4.src.tar.gz
# Fri, 01 Jul 2016 19:29:13 GMT
ENV GOLANG_SRC_SHA256=002acabce7ddc140d0d55891f9d4fcfbdd806b9332fb8b110c91bc91afb0bc93
# Fri, 01 Jul 2016 19:30:28 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& ./make.bash 		&& apk del .build-deps
# Fri, 01 Jul 2016 19:30:29 GMT
ENV GOPATH=/go
# Fri, 01 Jul 2016 19:30:30 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Fri, 01 Jul 2016 19:30:31 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Fri, 01 Jul 2016 19:30:32 GMT
WORKDIR /go
# Fri, 01 Jul 2016 19:30:33 GMT
COPY file:ce084cb461a5ff8443f1781f7b0af0a33ad2bd4fe7ca14df213f58fa79e0172b in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:189cf28ebbc5aee712ba9194f6308065957dcaff75ffd6fd1a66ebcfc3a0c9da`  
		Last Modified: Fri, 01 Jul 2016 19:34:34 GMT  
		Size: 65.6 MB (65624223 bytes)
	-	`sha256:11843d4b6571391fafc5bc609948e2b607d974a803127d39078522b990777af3`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 122.0 B
	-	`sha256:c1d9d7c9cb3e4bfbd999a501cf1746f7e3eba20f13544a38dff7c8c274711cfe`  
		Last Modified: Fri, 01 Jul 2016 19:34:12 GMT  
		Size: 1.3 KB (1348 bytes)

## `golang:1.6.3`

```console
$ docker pull golang@sha256:082c2c1e362cea02721a725d433609be0271caa586016c9167b224745b7ad091
```

-	Platforms:
	-	linux; amd64

### `golang:1.6.3` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:bc1c55b17233e0da5ca2f2f2d75d9e0a0549efc2424b78ace2f1828ae83c1ff5`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)

## `golang:1.6`

```console
$ docker pull golang@sha256:082c2c1e362cea02721a725d433609be0271caa586016c9167b224745b7ad091
```

-	Platforms:
	-	linux; amd64

### `golang:1.6` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:bc1c55b17233e0da5ca2f2f2d75d9e0a0549efc2424b78ace2f1828ae83c1ff5`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)

## `golang:1`

```console
$ docker pull golang@sha256:082c2c1e362cea02721a725d433609be0271caa586016c9167b224745b7ad091
```

-	Platforms:
	-	linux; amd64

### `golang:1` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:bc1c55b17233e0da5ca2f2f2d75d9e0a0549efc2424b78ace2f1828ae83c1ff5`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)

## `golang:latest`

```console
$ docker pull golang@sha256:082c2c1e362cea02721a725d433609be0271caa586016c9167b224745b7ad091
```

-	Platforms:
	-	linux; amd64

### `golang:latest` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217849 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:bc1c55b17233e0da5ca2f2f2d75d9e0a0549efc2424b78ace2f1828ae83c1ff5`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)

## `golang:1.6.3-onbuild`

```console
$ docker pull golang@sha256:3f651cbac34479e0c8e551d6ff140ce62b9d42bc2abe9f8ec3065f76263fa5e7
```

-	Platforms:
	-	linux; amd64

### `golang:1.6.3-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217981 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:71db94ad1fc7c3131d134b1038391ead8cc3b3b702fe248e4d904e0374095aa1`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:22:04 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:22:05 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:22:07 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)
	-	`sha256:3107dea7ebbcc53ec6d9a440752021f00465d89321a308d842368b04b5b26caa`  
		Last Modified: Mon, 18 Jul 2016 17:28:15 GMT  
		Size: 132.0 B

## `golang:1.6-onbuild`

```console
$ docker pull golang@sha256:3f651cbac34479e0c8e551d6ff140ce62b9d42bc2abe9f8ec3065f76263fa5e7
```

-	Platforms:
	-	linux; amd64

### `golang:1.6-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217981 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:71db94ad1fc7c3131d134b1038391ead8cc3b3b702fe248e4d904e0374095aa1`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:22:04 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:22:05 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:22:07 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)
	-	`sha256:3107dea7ebbcc53ec6d9a440752021f00465d89321a308d842368b04b5b26caa`  
		Last Modified: Mon, 18 Jul 2016 17:28:15 GMT  
		Size: 132.0 B

## `golang:1-onbuild`

```console
$ docker pull golang@sha256:3f651cbac34479e0c8e551d6ff140ce62b9d42bc2abe9f8ec3065f76263fa5e7
```

-	Platforms:
	-	linux; amd64

### `golang:1-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217981 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:71db94ad1fc7c3131d134b1038391ead8cc3b3b702fe248e4d904e0374095aa1`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:22:04 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:22:05 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:22:07 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)
	-	`sha256:3107dea7ebbcc53ec6d9a440752021f00465d89321a308d842368b04b5b26caa`  
		Last Modified: Mon, 18 Jul 2016 17:28:15 GMT  
		Size: 132.0 B

## `golang:onbuild`

```console
$ docker pull golang@sha256:3f651cbac34479e0c8e551d6ff140ce62b9d42bc2abe9f8ec3065f76263fa5e7
```

-	Platforms:
	-	linux; amd64

### `golang:onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **254.2 MB (254217981 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:71db94ad1fc7c3131d134b1038391ead8cc3b3b702fe248e4d904e0374095aa1`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:21:47 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:21:48 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:21:58 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:21:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:21:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:01 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:22:04 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:22:05 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:22:06 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:22:07 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:8de7f020474f46d9cad5ba9e857ce6b419fe7ebe6750537017a0baab74dca41d`  
		Last Modified: Mon, 18 Jul 2016 17:27:31 GMT  
		Size: 84.9 MB (84869316 bytes)
	-	`sha256:b98e09a07b43ec2163242552c60bfc06756167803dea74da9fbf398bac2de955`  
		Last Modified: Mon, 18 Jul 2016 17:27:06 GMT  
		Size: 122.0 B
	-	`sha256:c54fa659b43363d45d8703b9dacb587e90a33c95b977d151d1e07b015a211a6a`  
		Last Modified: Mon, 18 Jul 2016 17:27:05 GMT  
		Size: 1.4 KB (1354 bytes)
	-	`sha256:3107dea7ebbcc53ec6d9a440752021f00465d89321a308d842368b04b5b26caa`  
		Last Modified: Mon, 18 Jul 2016 17:28:15 GMT  
		Size: 132.0 B

## `golang:1.6.3-wheezy`

```console
$ docker pull golang@sha256:3acd4267fb69a83135473b73360d4f2e5a770cca77213bfadbad463373dfcc3b
```

-	Platforms:
	-	linux; amd64

### `golang:1.6.3-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **200.2 MB (200191983 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:703a7d47c681e143c9c9b0e74452d91d6f47d180b5b5dbc518b955d1b11d2a83`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:22:07 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:22:19 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:22:20 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:22:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6835d4689ee6a178ee8b623b820c2da17ff878c15409088058a1b02a78c14a60`  
		Last Modified: Mon, 18 Jul 2016 17:29:22 GMT  
		Size: 84.9 MB (84869321 bytes)
	-	`sha256:e4d50b03a1e6009a8da7a921cb56ee7f0ddcb06efec5c2695abbfc7aaba31896`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 123.0 B
	-	`sha256:cc6d1dc713952de7adfe5d32b7b5bc1375e2c2bbed4252def805b0eae5a8c3ad`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 1.4 KB (1353 bytes)

## `golang:1.6-wheezy`

```console
$ docker pull golang@sha256:3acd4267fb69a83135473b73360d4f2e5a770cca77213bfadbad463373dfcc3b
```

-	Platforms:
	-	linux; amd64

### `golang:1.6-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **200.2 MB (200191983 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:703a7d47c681e143c9c9b0e74452d91d6f47d180b5b5dbc518b955d1b11d2a83`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:22:07 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:22:19 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:22:20 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:22:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6835d4689ee6a178ee8b623b820c2da17ff878c15409088058a1b02a78c14a60`  
		Last Modified: Mon, 18 Jul 2016 17:29:22 GMT  
		Size: 84.9 MB (84869321 bytes)
	-	`sha256:e4d50b03a1e6009a8da7a921cb56ee7f0ddcb06efec5c2695abbfc7aaba31896`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 123.0 B
	-	`sha256:cc6d1dc713952de7adfe5d32b7b5bc1375e2c2bbed4252def805b0eae5a8c3ad`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 1.4 KB (1353 bytes)

## `golang:1-wheezy`

```console
$ docker pull golang@sha256:3acd4267fb69a83135473b73360d4f2e5a770cca77213bfadbad463373dfcc3b
```

-	Platforms:
	-	linux; amd64

### `golang:1-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **200.2 MB (200191983 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:703a7d47c681e143c9c9b0e74452d91d6f47d180b5b5dbc518b955d1b11d2a83`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:22:07 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:22:19 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:22:20 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:22:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6835d4689ee6a178ee8b623b820c2da17ff878c15409088058a1b02a78c14a60`  
		Last Modified: Mon, 18 Jul 2016 17:29:22 GMT  
		Size: 84.9 MB (84869321 bytes)
	-	`sha256:e4d50b03a1e6009a8da7a921cb56ee7f0ddcb06efec5c2695abbfc7aaba31896`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 123.0 B
	-	`sha256:cc6d1dc713952de7adfe5d32b7b5bc1375e2c2bbed4252def805b0eae5a8c3ad`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 1.4 KB (1353 bytes)

## `golang:wheezy`

```console
$ docker pull golang@sha256:3acd4267fb69a83135473b73360d4f2e5a770cca77213bfadbad463373dfcc3b
```

-	Platforms:
	-	linux; amd64

### `golang:wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **200.2 MB (200191983 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:703a7d47c681e143c9c9b0e74452d91d6f47d180b5b5dbc518b955d1b11d2a83`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:22:07 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.6.3.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:22:08 GMT
ENV GOLANG_DOWNLOAD_SHA256=cdde5e08530c0579255d6153b08fdb3b8e47caabbe717bc7bcd7561275a87aeb
# Mon, 18 Jul 2016 17:22:19 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:22:20 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:22:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:22:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:22:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:22:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:6835d4689ee6a178ee8b623b820c2da17ff878c15409088058a1b02a78c14a60`  
		Last Modified: Mon, 18 Jul 2016 17:29:22 GMT  
		Size: 84.9 MB (84869321 bytes)
	-	`sha256:e4d50b03a1e6009a8da7a921cb56ee7f0ddcb06efec5c2695abbfc7aaba31896`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 123.0 B
	-	`sha256:cc6d1dc713952de7adfe5d32b7b5bc1375e2c2bbed4252def805b0eae5a8c3ad`  
		Last Modified: Mon, 18 Jul 2016 17:28:56 GMT  
		Size: 1.4 KB (1353 bytes)

## `golang:1.6.3-alpine`

```console
$ docker pull golang@sha256:8b9e1e4a137e7663c1dc52a33c41699661ea4da9aca6ab0771b1fcec16a87535
```

-	Platforms:
	-	linux; amd64

### `golang:1.6.3-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.2 MB (72155824 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:6b317e0ae72cec6ec5faa748ae736e1d401735b1dc4eab2c633925ec109b0310`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:22:23 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6.3.src.tar.gz
# Mon, 18 Jul 2016 17:22:25 GMT
ENV GOLANG_SRC_SHA256=6326aeed5f86cf18f16d6dc831405614f855e2d416a91fd3fdc334f772345b00
# Mon, 18 Jul 2016 17:22:26 GMT
COPY file:b2d7156cdbff1193fb20efaf40b201017b0396eb5b2e0adb97970615a8fcf61d in /
# Mon, 18 Jul 2016 17:23:41 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:23:42 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:42 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:23:44 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:23:44 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:23:44 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:de90fc0e5164ab0874b9c887c660857517ef58d35f6506efa6a3c1f086898b99`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 444.0 B
	-	`sha256:e8f38fc389bc155298999428131401648c7470563a4571a304ae564b8cc0ba71`  
		Last Modified: Mon, 18 Jul 2016 17:30:28 GMT  
		Size: 69.5 MB (69499701 bytes)
	-	`sha256:087a26f98166190888614f96fb10b95c33c46d1943a6b81a7c66134bd22efa2d`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 122.0 B
	-	`sha256:25994cc119744e0d02f5716206b622761006e0fe842624fc0343b68fcbe76804`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 1.3 KB (1347 bytes)

## `golang:1.6-alpine`

```console
$ docker pull golang@sha256:8b9e1e4a137e7663c1dc52a33c41699661ea4da9aca6ab0771b1fcec16a87535
```

-	Platforms:
	-	linux; amd64

### `golang:1.6-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.2 MB (72155824 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:6b317e0ae72cec6ec5faa748ae736e1d401735b1dc4eab2c633925ec109b0310`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:22:23 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6.3.src.tar.gz
# Mon, 18 Jul 2016 17:22:25 GMT
ENV GOLANG_SRC_SHA256=6326aeed5f86cf18f16d6dc831405614f855e2d416a91fd3fdc334f772345b00
# Mon, 18 Jul 2016 17:22:26 GMT
COPY file:b2d7156cdbff1193fb20efaf40b201017b0396eb5b2e0adb97970615a8fcf61d in /
# Mon, 18 Jul 2016 17:23:41 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:23:42 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:42 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:23:44 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:23:44 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:23:44 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:de90fc0e5164ab0874b9c887c660857517ef58d35f6506efa6a3c1f086898b99`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 444.0 B
	-	`sha256:e8f38fc389bc155298999428131401648c7470563a4571a304ae564b8cc0ba71`  
		Last Modified: Mon, 18 Jul 2016 17:30:28 GMT  
		Size: 69.5 MB (69499701 bytes)
	-	`sha256:087a26f98166190888614f96fb10b95c33c46d1943a6b81a7c66134bd22efa2d`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 122.0 B
	-	`sha256:25994cc119744e0d02f5716206b622761006e0fe842624fc0343b68fcbe76804`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 1.3 KB (1347 bytes)

## `golang:1-alpine`

```console
$ docker pull golang@sha256:8b9e1e4a137e7663c1dc52a33c41699661ea4da9aca6ab0771b1fcec16a87535
```

-	Platforms:
	-	linux; amd64

### `golang:1-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.2 MB (72155824 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:6b317e0ae72cec6ec5faa748ae736e1d401735b1dc4eab2c633925ec109b0310`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:22:23 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6.3.src.tar.gz
# Mon, 18 Jul 2016 17:22:25 GMT
ENV GOLANG_SRC_SHA256=6326aeed5f86cf18f16d6dc831405614f855e2d416a91fd3fdc334f772345b00
# Mon, 18 Jul 2016 17:22:26 GMT
COPY file:b2d7156cdbff1193fb20efaf40b201017b0396eb5b2e0adb97970615a8fcf61d in /
# Mon, 18 Jul 2016 17:23:41 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:23:42 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:42 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:23:44 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:23:44 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:23:44 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:de90fc0e5164ab0874b9c887c660857517ef58d35f6506efa6a3c1f086898b99`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 444.0 B
	-	`sha256:e8f38fc389bc155298999428131401648c7470563a4571a304ae564b8cc0ba71`  
		Last Modified: Mon, 18 Jul 2016 17:30:28 GMT  
		Size: 69.5 MB (69499701 bytes)
	-	`sha256:087a26f98166190888614f96fb10b95c33c46d1943a6b81a7c66134bd22efa2d`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 122.0 B
	-	`sha256:25994cc119744e0d02f5716206b622761006e0fe842624fc0343b68fcbe76804`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 1.3 KB (1347 bytes)

## `golang:alpine`

```console
$ docker pull golang@sha256:8b9e1e4a137e7663c1dc52a33c41699661ea4da9aca6ab0771b1fcec16a87535
```

-	Platforms:
	-	linux; amd64

### `golang:alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.2 MB (72155824 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:6b317e0ae72cec6ec5faa748ae736e1d401735b1dc4eab2c633925ec109b0310`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:22:23 GMT
ENV GOLANG_VERSION=1.6.3
# Mon, 18 Jul 2016 17:22:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.6.3.src.tar.gz
# Mon, 18 Jul 2016 17:22:25 GMT
ENV GOLANG_SRC_SHA256=6326aeed5f86cf18f16d6dc831405614f855e2d416a91fd3fdc334f772345b00
# Mon, 18 Jul 2016 17:22:26 GMT
COPY file:b2d7156cdbff1193fb20efaf40b201017b0396eb5b2e0adb97970615a8fcf61d in /
# Mon, 18 Jul 2016 17:23:41 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:23:42 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:42 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:23:44 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:23:44 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:23:44 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:de90fc0e5164ab0874b9c887c660857517ef58d35f6506efa6a3c1f086898b99`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 444.0 B
	-	`sha256:e8f38fc389bc155298999428131401648c7470563a4571a304ae564b8cc0ba71`  
		Last Modified: Mon, 18 Jul 2016 17:30:28 GMT  
		Size: 69.5 MB (69499701 bytes)
	-	`sha256:087a26f98166190888614f96fb10b95c33c46d1943a6b81a7c66134bd22efa2d`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 122.0 B
	-	`sha256:25994cc119744e0d02f5716206b622761006e0fe842624fc0343b68fcbe76804`  
		Last Modified: Mon, 18 Jul 2016 17:30:04 GMT  
		Size: 1.3 KB (1347 bytes)

## `golang:1.7rc2`

```console
$ docker pull golang@sha256:ed9f530f21851aeecc55702ef1dd923c3ada7439a481980bf662796b217b5524
```

-	Platforms:
	-	linux; amd64

### `golang:1.7rc2` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **250.8 MB (250828904 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:faa2267eee5c841a611aadeff6eeeb76e004b27eb096923a73c59d14c34a9673`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:23:45 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:23:56 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:23:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:00 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:849f2fd9999a429eb75e0f2f2f4a9f915f4d57e7adfb6a70c5ae07199ef79718`  
		Last Modified: Mon, 18 Jul 2016 17:31:37 GMT  
		Size: 81.5 MB (81480370 bytes)
	-	`sha256:d8e6b9738392865470b87317b0a4ec3008426defc7d867b65ea7f41a442f6e50`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 122.0 B
	-	`sha256:d1100a4447aec4d828b6540be79314f679d8d6176c293c38dbc1648728f237b8`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 1.4 KB (1355 bytes)

## `golang:1.7`

```console
$ docker pull golang@sha256:ed9f530f21851aeecc55702ef1dd923c3ada7439a481980bf662796b217b5524
```

-	Platforms:
	-	linux; amd64

### `golang:1.7` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **250.8 MB (250828904 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:faa2267eee5c841a611aadeff6eeeb76e004b27eb096923a73c59d14c34a9673`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:23:45 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:23:56 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:23:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:00 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:849f2fd9999a429eb75e0f2f2f4a9f915f4d57e7adfb6a70c5ae07199ef79718`  
		Last Modified: Mon, 18 Jul 2016 17:31:37 GMT  
		Size: 81.5 MB (81480370 bytes)
	-	`sha256:d8e6b9738392865470b87317b0a4ec3008426defc7d867b65ea7f41a442f6e50`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 122.0 B
	-	`sha256:d1100a4447aec4d828b6540be79314f679d8d6176c293c38dbc1648728f237b8`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 1.4 KB (1355 bytes)

## `golang:1.7rc2-onbuild`

```console
$ docker pull golang@sha256:80c1be7d123028d2136b80ced5ec25208945b2b5676a1ac35ad98f25295d98e7
```

-	Platforms:
	-	linux; amd64

### `golang:1.7rc2-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **250.8 MB (250829036 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a7edffeb91cdbf807ea6aef0e2a521b3dd1090cbf6149d830f68c119368aaa25`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:23:45 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:23:56 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:23:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:00 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:24:03 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:24:03 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:24:04 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:24:04 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:24:05 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:24:05 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:849f2fd9999a429eb75e0f2f2f4a9f915f4d57e7adfb6a70c5ae07199ef79718`  
		Last Modified: Mon, 18 Jul 2016 17:31:37 GMT  
		Size: 81.5 MB (81480370 bytes)
	-	`sha256:d8e6b9738392865470b87317b0a4ec3008426defc7d867b65ea7f41a442f6e50`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 122.0 B
	-	`sha256:d1100a4447aec4d828b6540be79314f679d8d6176c293c38dbc1648728f237b8`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 1.4 KB (1355 bytes)
	-	`sha256:e1856adcf1e09ddd804838c4e72db1b5621c8fa974c0350dafa08566f91c3b2e`  
		Last Modified: Mon, 18 Jul 2016 17:32:02 GMT  
		Size: 132.0 B

## `golang:1.7-onbuild`

```console
$ docker pull golang@sha256:80c1be7d123028d2136b80ced5ec25208945b2b5676a1ac35ad98f25295d98e7
```

-	Platforms:
	-	linux; amd64

### `golang:1.7-onbuild` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **250.8 MB (250829036 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a7edffeb91cdbf807ea6aef0e2a521b3dd1090cbf6149d830f68c119368aaa25`
-	Default Command: `["go-wrapper","run"]`

```dockerfile
# Thu, 09 Jun 2016 21:28:42 GMT
ADD file:76679eeb94129df23c99013487d6b6bd779d2107bf07d194a524fdbb6a961530 in /
# Thu, 09 Jun 2016 21:28:43 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:35:50 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:37:09 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:11 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:23:45 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:23:46 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:23:56 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:23:59 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:23:59 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:00 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:01 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:01 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
# Mon, 18 Jul 2016 17:24:03 GMT
RUN mkdir -p /go/src/app
# Mon, 18 Jul 2016 17:24:03 GMT
WORKDIR /go/src/app
# Mon, 18 Jul 2016 17:24:04 GMT
CMD ["go-wrapper" "run"]
# Mon, 18 Jul 2016 17:24:04 GMT
ONBUILD COPY . /go/src/app
# Mon, 18 Jul 2016 17:24:05 GMT
ONBUILD RUN go-wrapper download
# Mon, 18 Jul 2016 17:24:05 GMT
ONBUILD RUN go-wrapper install
```

-	Layers:
	-	`sha256:5c90d4a2d1a8dfffd05ff2dd659923f0ca2d843b5e45d030e17abbcd06a11b5b`  
		Last Modified: Thu, 09 Jun 2016 21:30:47 GMT  
		Size: 51.4 MB (51352535 bytes)
	-	`sha256:ab30c63719b10dd434ddbe896879bd9b637fe4e16749a94d3dc827450dc2a437`  
		Last Modified: Thu, 09 Jun 2016 21:46:24 GMT  
		Size: 18.5 MB (18547219 bytes)
	-	`sha256:c6072700a24252bd71f6c5d2cabf5978ddf324a959b05bad417d8b3789f8df33`  
		Last Modified: Thu, 09 Jun 2016 21:46:52 GMT  
		Size: 42.5 MB (42525371 bytes)
	-	`sha256:0ffc1204e0abead91aa6678abffa44739455c7b95b96b108eefc2f29d6001fdf`  
		Last Modified: Fri, 17 Jun 2016 16:50:25 GMT  
		Size: 56.9 MB (56921932 bytes)
	-	`sha256:849f2fd9999a429eb75e0f2f2f4a9f915f4d57e7adfb6a70c5ae07199ef79718`  
		Last Modified: Mon, 18 Jul 2016 17:31:37 GMT  
		Size: 81.5 MB (81480370 bytes)
	-	`sha256:d8e6b9738392865470b87317b0a4ec3008426defc7d867b65ea7f41a442f6e50`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 122.0 B
	-	`sha256:d1100a4447aec4d828b6540be79314f679d8d6176c293c38dbc1648728f237b8`  
		Last Modified: Mon, 18 Jul 2016 17:31:12 GMT  
		Size: 1.4 KB (1355 bytes)
	-	`sha256:e1856adcf1e09ddd804838c4e72db1b5621c8fa974c0350dafa08566f91c3b2e`  
		Last Modified: Mon, 18 Jul 2016 17:32:02 GMT  
		Size: 132.0 B

## `golang:1.7rc2-wheezy`

```console
$ docker pull golang@sha256:00a148ad7426fbebba1ae4155096278bbe3d5c1bae00c724f7224f7d3a720646
```

-	Platforms:
	-	linux; amd64

### `golang:1.7rc2-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **196.8 MB (196803037 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:ee4d40d9f93f46381b7b3facca7bcf973c62eb9e718acfc9480a16ac52fe9933`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:24:16 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:24:19 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:24:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:f5c35ed9d6ca6b5cedeebe9b73d2c13b9433ac5279df1e7cfaa03350a223de96`  
		Last Modified: Mon, 18 Jul 2016 17:32:50 GMT  
		Size: 81.5 MB (81480369 bytes)
	-	`sha256:5e714589694d5d13d11821c6889b1999a129042e3a23795ea1adfaaf3a7a5b06`  
		Last Modified: Mon, 18 Jul 2016 17:32:25 GMT  
		Size: 123.0 B
	-	`sha256:c283d8a4635fa11c1eed07c54a5880745b44c749ffd69f229cbf482c8093a7bc`  
		Last Modified: Mon, 18 Jul 2016 17:32:25 GMT  
		Size: 1.4 KB (1359 bytes)

## `golang:1.7-wheezy`

```console
$ docker pull golang@sha256:00a148ad7426fbebba1ae4155096278bbe3d5c1bae00c724f7224f7d3a720646
```

-	Platforms:
	-	linux; amd64

### `golang:1.7-wheezy` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **196.8 MB (196803037 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:ee4d40d9f93f46381b7b3facca7bcf973c62eb9e718acfc9480a16ac52fe9933`
-	Default Command: `["\/bin\/bash"]`

```dockerfile
# Thu, 09 Jun 2016 21:30:19 GMT
ADD file:add5fc8cb18678647f395d0a743c4ca93466b70b9e42847d850aa206b7ad0d8d in /
# Thu, 09 Jun 2016 21:30:20 GMT
CMD ["/bin/bash"]
# Thu, 09 Jun 2016 21:43:48 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		ca-certificates 		curl 		wget 	&& rm -rf /var/lib/apt/lists/*
# Thu, 09 Jun 2016 21:44:24 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		bzr 		git 		mercurial 		openssh-client 		subversion 				procps 	&& rm -rf /var/lib/apt/lists/*
# Fri, 10 Jun 2016 21:36:43 GMT
RUN apt-get update && apt-get install -y --no-install-recommends 		g++ 		gcc 		libc6-dev 		make 	&& rm -rf /var/lib/apt/lists/*
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_DOWNLOAD_URL=https://golang.org/dl/go1.7rc2.linux-amd64.tar.gz
# Mon, 18 Jul 2016 17:24:06 GMT
ENV GOLANG_DOWNLOAD_SHA256=145e486499d349757cbb7ae8dfeeea5d7a76f146f6c8880173fe3d0aacc5dd42
# Mon, 18 Jul 2016 17:24:16 GMT
RUN curl -fsSL "$GOLANG_DOWNLOAD_URL" -o golang.tar.gz 	&& echo "$GOLANG_DOWNLOAD_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz
# Mon, 18 Jul 2016 17:24:19 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:24:20 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:24:22 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:24:22 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:24:23 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:8ceedfe606fc6a2449001a47b33357a1aefaa3538bff8ce98af64fc6cd810225`  
		Last Modified: Thu, 09 Jun 2016 21:34:10 GMT  
		Size: 37.2 MB (37209549 bytes)
	-	`sha256:6523e37a38fa9bfac81a0773979ea1b66dce8df121a732b1c3c86c13965e00d6`  
		Last Modified: Thu, 09 Jun 2016 21:55:48 GMT  
		Size: 6.8 MB (6751390 bytes)
	-	`sha256:808895c4b06b9264d617f83d39d8c4dd8d8b4dccdb53102a49707851cd59db47`  
		Last Modified: Thu, 09 Jun 2016 21:56:11 GMT  
		Size: 37.4 MB (37389872 bytes)
	-	`sha256:bc6935f49a7a41d9d0a9e861e1ef40879eecc95cc5559e40e45c478ddf97bb8a`  
		Last Modified: Fri, 17 Jun 2016 16:51:24 GMT  
		Size: 34.0 MB (33970375 bytes)
	-	`sha256:f5c35ed9d6ca6b5cedeebe9b73d2c13b9433ac5279df1e7cfaa03350a223de96`  
		Last Modified: Mon, 18 Jul 2016 17:32:50 GMT  
		Size: 81.5 MB (81480369 bytes)
	-	`sha256:5e714589694d5d13d11821c6889b1999a129042e3a23795ea1adfaaf3a7a5b06`  
		Last Modified: Mon, 18 Jul 2016 17:32:25 GMT  
		Size: 123.0 B
	-	`sha256:c283d8a4635fa11c1eed07c54a5880745b44c749ffd69f229cbf482c8093a7bc`  
		Last Modified: Mon, 18 Jul 2016 17:32:25 GMT  
		Size: 1.4 KB (1359 bytes)

## `golang:1.7rc2-alpine`

```console
$ docker pull golang@sha256:68a545fd20e80c2c96ee35919ea95ab74c6da4b033e84b4ccce464166748776f
```

-	Platforms:
	-	linux; amd64

### `golang:1.7rc2-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.8 MB (72796361 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7ea82be6c98ea8088e0a3430245607eb1907390104d7e178d456213d161fce14`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:24:23 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:24:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.7rc2.src.tar.gz
# Mon, 18 Jul 2016 17:24:24 GMT
ENV GOLANG_SRC_SHA256=87bafefb093dd163d264099b39b1bcdc227f54f935b77f5ff74b0d57e3638da6
# Mon, 18 Jul 2016 17:24:25 GMT
COPY file:b54d7d4313a41e3729d6f4b7aa6e6f33a1e99759cb2a04149fae89f8211c3a65 in /
# Mon, 18 Jul 2016 17:25:40 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:25:40 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:25:41 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:25:42 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:25:42 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:25:43 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:2286ad410d37ae8f226db48261288c94db99badf479423d65ca92d52a4a1275f`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 437.0 B
	-	`sha256:ccd42a8a9e7bc7a0f2ea2367363ae968436f70f3fedc452e497b0ef8543b9f50`  
		Last Modified: Mon, 18 Jul 2016 17:33:38 GMT  
		Size: 70.1 MB (70140245 bytes)
	-	`sha256:0631a09039ff2cccf6045310c5cd4875eec2651551af476b76568681337c7520`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 122.0 B
	-	`sha256:4a7b9b35d74fd2c3a0329c5d282f022700060a2418b6707e3b7ecccfbf8081ab`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 1.3 KB (1347 bytes)

## `golang:1.7-alpine`

```console
$ docker pull golang@sha256:68a545fd20e80c2c96ee35919ea95ab74c6da4b033e84b4ccce464166748776f
```

-	Platforms:
	-	linux; amd64

### `golang:1.7-alpine` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **72.8 MB (72796361 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7ea82be6c98ea8088e0a3430245607eb1907390104d7e178d456213d161fce14`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Fri, 01 Jul 2016 19:29:12 GMT
RUN apk add --no-cache ca-certificates
# Mon, 18 Jul 2016 17:24:23 GMT
ENV GOLANG_VERSION=1.7rc2
# Mon, 18 Jul 2016 17:24:24 GMT
ENV GOLANG_SRC_URL=https://golang.org/dl/go1.7rc2.src.tar.gz
# Mon, 18 Jul 2016 17:24:24 GMT
ENV GOLANG_SRC_SHA256=87bafefb093dd163d264099b39b1bcdc227f54f935b77f5ff74b0d57e3638da6
# Mon, 18 Jul 2016 17:24:25 GMT
COPY file:b54d7d4313a41e3729d6f4b7aa6e6f33a1e99759cb2a04149fae89f8211c3a65 in /
# Mon, 18 Jul 2016 17:25:40 GMT
RUN set -ex 	&& apk add --no-cache --virtual .build-deps 		bash 		gcc 		musl-dev 		openssl 		go 		&& export GOROOT_BOOTSTRAP="$(go env GOROOT)" 		&& wget -q "$GOLANG_SRC_URL" -O golang.tar.gz 	&& echo "$GOLANG_SRC_SHA256  golang.tar.gz" | sha256sum -c - 	&& tar -C /usr/local -xzf golang.tar.gz 	&& rm golang.tar.gz 	&& cd /usr/local/go/src 	&& patch -p2 -i /no-pic.patch 	&& ./make.bash 		&& rm -rf /*.patch 	&& apk del .build-deps
# Mon, 18 Jul 2016 17:25:40 GMT
ENV GOPATH=/go
# Mon, 18 Jul 2016 17:25:41 GMT
ENV PATH=/go/bin:/usr/local/go/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
# Mon, 18 Jul 2016 17:25:42 GMT
RUN mkdir -p "$GOPATH/src" "$GOPATH/bin" && chmod -R 777 "$GOPATH"
# Mon, 18 Jul 2016 17:25:42 GMT
WORKDIR /go
# Mon, 18 Jul 2016 17:25:43 GMT
COPY file:f6191f2c86edc9343569339f101facba47e886e33e29d70da6916ca6b1101a53 in /usr/local/bin/
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:ac58758e6ad5928c40fe2ce1b955a5f9d1c4889667874887960ff0c00f2ebcf6`  
		Last Modified: Fri, 01 Jul 2016 19:34:13 GMT  
		Size: 343.9 KB (343924 bytes)
	-	`sha256:2286ad410d37ae8f226db48261288c94db99badf479423d65ca92d52a4a1275f`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 437.0 B
	-	`sha256:ccd42a8a9e7bc7a0f2ea2367363ae968436f70f3fedc452e497b0ef8543b9f50`  
		Last Modified: Mon, 18 Jul 2016 17:33:38 GMT  
		Size: 70.1 MB (70140245 bytes)
	-	`sha256:0631a09039ff2cccf6045310c5cd4875eec2651551af476b76568681337c7520`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 122.0 B
	-	`sha256:4a7b9b35d74fd2c3a0329c5d282f022700060a2418b6707e3b7ecccfbf8081ab`  
		Last Modified: Mon, 18 Jul 2016 17:33:15 GMT  
		Size: 1.3 KB (1347 bytes)

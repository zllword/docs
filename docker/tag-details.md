<!-- THIS FILE IS GENERATED VIA '.template-helpers/generate-tag-details.pl' -->

# Tags of `docker`

-	[`docker:1.12.0-rc4`](#docker1120-rc4)
-	[`docker:1.12-rc`](#docker112-rc)
-	[`docker:rc`](#dockerrc)
-	[`docker:1.12.0-rc4-dind`](#docker1120-rc4-dind)
-	[`docker:1.12-rc-dind`](#docker112-rc-dind)
-	[`docker:rc-dind`](#dockerrc-dind)
-	[`docker:1.12.0-rc4-git`](#docker1120-rc4-git)
-	[`docker:1.12-rc-git`](#docker112-rc-git)
-	[`docker:rc-git`](#dockerrc-git)
-	[`docker:1.11.2`](#docker1112)
-	[`docker:1.11`](#docker111)
-	[`docker:1`](#docker1)
-	[`docker:latest`](#dockerlatest)
-	[`docker:1.11.2-dind`](#docker1112-dind)
-	[`docker:1.11-dind`](#docker111-dind)
-	[`docker:1-dind`](#docker1-dind)
-	[`docker:dind`](#dockerdind)
-	[`docker:1.11.2-git`](#docker1112-git)
-	[`docker:1.11-git`](#docker111-git)
-	[`docker:1-git`](#docker1-git)
-	[`docker:git`](#dockergit)
-	[`docker:1.10.3`](#docker1103)
-	[`docker:1.10`](#docker110)
-	[`docker:1.10.3-dind`](#docker1103-dind)
-	[`docker:1.10-dind`](#docker110-dind)
-	[`docker:1.10.3-git`](#docker1103-git)
-	[`docker:1.10-git`](#docker110-git)

## `docker:1.12.0-rc4`

**does not exist** (yet?)

## `docker:1.12-rc`

```console
$ docker pull docker@sha256:2080067f458688c1caf0ca8e2e35bce709c83852c691eafe2c4901aecbe1ad90
```

-	Platforms:
	-	linux; amd64

### `docker:1.12-rc` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **30.9 MB (30948798 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:449c2403515d50bb50d42a219690b06891ed5fe99c4c6ed98ff66b16a563a778`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B

## `docker:rc`

```console
$ docker pull docker@sha256:2080067f458688c1caf0ca8e2e35bce709c83852c691eafe2c4901aecbe1ad90
```

-	Platforms:
	-	linux; amd64

### `docker:rc` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **30.9 MB (30948798 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:449c2403515d50bb50d42a219690b06891ed5fe99c4c6ed98ff66b16a563a778`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B

## `docker:1.12.0-rc4-dind`

**does not exist** (yet?)

## `docker:1.12-rc-dind`

```console
$ docker pull docker@sha256:40aca152583dc5ac5759cd3eb505d16555b144af9a2f27d72a34699405fda9c6
```

-	Platforms:
	-	linux; amd64

### `docker:1.12-rc-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **33.0 MB (33038664 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a1d5454931ebf228ee871e13981dedb3e8af7c1877857be1957024361d235456`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
# Tue, 05 Jul 2016 17:48:57 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Tue, 05 Jul 2016 17:48:59 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Tue, 05 Jul 2016 17:48:59 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Tue, 05 Jul 2016 17:49:00 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Tue, 05 Jul 2016 17:49:01 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Tue, 05 Jul 2016 17:49:01 GMT
VOLUME [/var/lib/docker]
# Tue, 05 Jul 2016 17:49:01 GMT
EXPOSE 2375/tcp
# Tue, 05 Jul 2016 17:49:02 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:49:02 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B
	-	`sha256:eb140144d2586912ef0c6f253b6f689a5470c95969ac0419556a68bd1476e3c7`  
		Last Modified: Tue, 05 Jul 2016 17:49:56 GMT  
		Size: 2.1 MB (2065069 bytes)
	-	`sha256:30231dad89daffc94d007effb63827e7a02b70706097fe8555e1d833c6af4994`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 22.5 KB (22541 bytes)
	-	`sha256:343a057991c0aae2bea20c5340e46fb74fe667f43f35b6331b46618637063429`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 1.8 KB (1820 bytes)
	-	`sha256:be3e2e8ef43537911b48ca8611197e8d925c880d5ede1ee16be294f8fcf64d2f`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 436.0 B

## `docker:rc-dind`

```console
$ docker pull docker@sha256:40aca152583dc5ac5759cd3eb505d16555b144af9a2f27d72a34699405fda9c6
```

-	Platforms:
	-	linux; amd64

### `docker:rc-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **33.0 MB (33038664 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a1d5454931ebf228ee871e13981dedb3e8af7c1877857be1957024361d235456`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
# Tue, 05 Jul 2016 17:48:57 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Tue, 05 Jul 2016 17:48:59 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Tue, 05 Jul 2016 17:48:59 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Tue, 05 Jul 2016 17:49:00 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Tue, 05 Jul 2016 17:49:01 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Tue, 05 Jul 2016 17:49:01 GMT
VOLUME [/var/lib/docker]
# Tue, 05 Jul 2016 17:49:01 GMT
EXPOSE 2375/tcp
# Tue, 05 Jul 2016 17:49:02 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:49:02 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B
	-	`sha256:eb140144d2586912ef0c6f253b6f689a5470c95969ac0419556a68bd1476e3c7`  
		Last Modified: Tue, 05 Jul 2016 17:49:56 GMT  
		Size: 2.1 MB (2065069 bytes)
	-	`sha256:30231dad89daffc94d007effb63827e7a02b70706097fe8555e1d833c6af4994`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 22.5 KB (22541 bytes)
	-	`sha256:343a057991c0aae2bea20c5340e46fb74fe667f43f35b6331b46618637063429`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 1.8 KB (1820 bytes)
	-	`sha256:be3e2e8ef43537911b48ca8611197e8d925c880d5ede1ee16be294f8fcf64d2f`  
		Last Modified: Tue, 05 Jul 2016 17:49:55 GMT  
		Size: 436.0 B

## `docker:1.12.0-rc4-git`

**does not exist** (yet?)

## `docker:1.12-rc-git`

```console
$ docker pull docker@sha256:2c99a5d62b3778f2ec5e093f6536e847574a606100793626597d942c6ad776f3
```

-	Platforms:
	-	linux; amd64

### `docker:1.12-rc-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **40.1 MB (40087227 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7b6a7142f2bfa1aaafe22b99cb2a748c6023222e25f02e583e3957d38db0859b`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
# Tue, 05 Jul 2016 17:49:06 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B
	-	`sha256:0d1ea630d409e6b2e4a7612ab96e505a04e539bc75a3dbe97504937353e958ef`  
		Last Modified: Tue, 05 Jul 2016 17:50:28 GMT  
		Size: 9.1 MB (9138429 bytes)

## `docker:rc-git`

```console
$ docker pull docker@sha256:2c99a5d62b3778f2ec5e093f6536e847574a606100793626597d942c6ad776f3
```

-	Platforms:
	-	linux; amd64

### `docker:rc-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **40.1 MB (40087227 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:7b6a7142f2bfa1aaafe22b99cb2a748c6023222e25f02e583e3957d38db0859b`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:17:12 GMT
ENV DOCKER_BUCKET=test.docker.com
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_VERSION=1.12.0-rc3
# Tue, 05 Jul 2016 17:48:46 GMT
ENV DOCKER_SHA256=3b4f6318c3d721766ae121bf0627f51d8c2565ee1875b3144950bb8120c77344
# Tue, 05 Jul 2016 17:48:50 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Tue, 05 Jul 2016 17:48:51 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Tue, 05 Jul 2016 17:48:51 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Tue, 05 Jul 2016 17:48:51 GMT
CMD ["sh"]
# Tue, 05 Jul 2016 17:49:06 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:3ddfb2a13daee7dd2f53b5507dcfd10991e081e3ea262481832af804a856084e`  
		Last Modified: Tue, 05 Jul 2016 17:49:26 GMT  
		Size: 27.7 MB (27725038 bytes)
	-	`sha256:68e46a25e8e339c15307bfd8128c5ff3cb8d8cdacd7522624773472ce54b4622`  
		Last Modified: Tue, 05 Jul 2016 17:49:16 GMT  
		Size: 466.0 B
	-	`sha256:0d1ea630d409e6b2e4a7612ab96e505a04e539bc75a3dbe97504937353e958ef`  
		Last Modified: Tue, 05 Jul 2016 17:50:28 GMT  
		Size: 9.1 MB (9138429 bytes)

## `docker:1.11.2`

```console
$ docker pull docker@sha256:8ea16b052a980e935bc32607f0b011196a56f416130e9480d942f288db6506e1
```

-	Platforms:
	-	linux; amd64

### `docker:1.11.2` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **23.7 MB (23673466 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b7b7422b4d51afbf910dbc29640d65bf973432f1bc395faf864dd1be3f0866fe`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B

## `docker:1.11`

```console
$ docker pull docker@sha256:8ea16b052a980e935bc32607f0b011196a56f416130e9480d942f288db6506e1
```

-	Platforms:
	-	linux; amd64

### `docker:1.11` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **23.7 MB (23673466 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b7b7422b4d51afbf910dbc29640d65bf973432f1bc395faf864dd1be3f0866fe`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B

## `docker:1`

```console
$ docker pull docker@sha256:8ea16b052a980e935bc32607f0b011196a56f416130e9480d942f288db6506e1
```

-	Platforms:
	-	linux; amd64

### `docker:1` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **23.7 MB (23673466 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b7b7422b4d51afbf910dbc29640d65bf973432f1bc395faf864dd1be3f0866fe`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B

## `docker:latest`

```console
$ docker pull docker@sha256:8ea16b052a980e935bc32607f0b011196a56f416130e9480d942f288db6506e1
```

-	Platforms:
	-	linux; amd64

### `docker:latest` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **23.7 MB (23673466 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:b7b7422b4d51afbf910dbc29640d65bf973432f1bc395faf864dd1be3f0866fe`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B

## `docker:1.11.2-dind`

```console
$ docker pull docker@sha256:fc8971f1d9c3d075cca5f36600d1053f8a716bf26b97740a758c596be377b446
```

-	Platforms:
	-	linux; amd64

### `docker:1.11.2-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **25.8 MB (25763261 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5fc60c35ab566212e8eceb74d53eee52981f340670f064d9d8a95b21bf5e2c5`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:16:53 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:45 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:45 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:47 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:47 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:47 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:48 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:48 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:48 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:35a39bc3386b3b69bcd12abc45f6243603645b67ebd20e9cd40b2cfc70c67ef2`  
		Last Modified: Thu, 23 Jun 2016 22:17:06 GMT  
		Size: 2.1 MB (2065036 bytes)
	-	`sha256:5b1373dd4d7eee6f3833e38ee94c43d01d8f9af9c6c0a702a502224cafececec`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 22.5 KB (22502 bytes)
	-	`sha256:4af5af3d425e3c0368ef84517cb3f421b220b3b5d367ddda090667ac630c678d`  
		Last Modified: Fri, 01 Jul 2016 19:22:49 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:625b3a7c30d5e76b58a6b84dcb61983885db3b7229e218906ea625e657d047a3`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 436.0 B

## `docker:1.11-dind`

```console
$ docker pull docker@sha256:fc8971f1d9c3d075cca5f36600d1053f8a716bf26b97740a758c596be377b446
```

-	Platforms:
	-	linux; amd64

### `docker:1.11-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **25.8 MB (25763261 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5fc60c35ab566212e8eceb74d53eee52981f340670f064d9d8a95b21bf5e2c5`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:16:53 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:45 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:45 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:47 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:47 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:47 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:48 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:48 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:48 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:35a39bc3386b3b69bcd12abc45f6243603645b67ebd20e9cd40b2cfc70c67ef2`  
		Last Modified: Thu, 23 Jun 2016 22:17:06 GMT  
		Size: 2.1 MB (2065036 bytes)
	-	`sha256:5b1373dd4d7eee6f3833e38ee94c43d01d8f9af9c6c0a702a502224cafececec`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 22.5 KB (22502 bytes)
	-	`sha256:4af5af3d425e3c0368ef84517cb3f421b220b3b5d367ddda090667ac630c678d`  
		Last Modified: Fri, 01 Jul 2016 19:22:49 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:625b3a7c30d5e76b58a6b84dcb61983885db3b7229e218906ea625e657d047a3`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 436.0 B

## `docker:1-dind`

```console
$ docker pull docker@sha256:fc8971f1d9c3d075cca5f36600d1053f8a716bf26b97740a758c596be377b446
```

-	Platforms:
	-	linux; amd64

### `docker:1-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **25.8 MB (25763261 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5fc60c35ab566212e8eceb74d53eee52981f340670f064d9d8a95b21bf5e2c5`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:16:53 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:45 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:45 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:47 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:47 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:47 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:48 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:48 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:48 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:35a39bc3386b3b69bcd12abc45f6243603645b67ebd20e9cd40b2cfc70c67ef2`  
		Last Modified: Thu, 23 Jun 2016 22:17:06 GMT  
		Size: 2.1 MB (2065036 bytes)
	-	`sha256:5b1373dd4d7eee6f3833e38ee94c43d01d8f9af9c6c0a702a502224cafececec`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 22.5 KB (22502 bytes)
	-	`sha256:4af5af3d425e3c0368ef84517cb3f421b220b3b5d367ddda090667ac630c678d`  
		Last Modified: Fri, 01 Jul 2016 19:22:49 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:625b3a7c30d5e76b58a6b84dcb61983885db3b7229e218906ea625e657d047a3`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 436.0 B

## `docker:dind`

```console
$ docker pull docker@sha256:fc8971f1d9c3d075cca5f36600d1053f8a716bf26b97740a758c596be377b446
```

-	Platforms:
	-	linux; amd64

### `docker:dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **25.8 MB (25763261 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:a5fc60c35ab566212e8eceb74d53eee52981f340670f064d9d8a95b21bf5e2c5`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:16:53 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:45 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:45 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:47 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:47 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:47 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:48 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:48 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:48 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:35a39bc3386b3b69bcd12abc45f6243603645b67ebd20e9cd40b2cfc70c67ef2`  
		Last Modified: Thu, 23 Jun 2016 22:17:06 GMT  
		Size: 2.1 MB (2065036 bytes)
	-	`sha256:5b1373dd4d7eee6f3833e38ee94c43d01d8f9af9c6c0a702a502224cafececec`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 22.5 KB (22502 bytes)
	-	`sha256:4af5af3d425e3c0368ef84517cb3f421b220b3b5d367ddda090667ac630c678d`  
		Last Modified: Fri, 01 Jul 2016 19:22:49 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:625b3a7c30d5e76b58a6b84dcb61983885db3b7229e218906ea625e657d047a3`  
		Last Modified: Fri, 01 Jul 2016 19:22:48 GMT  
		Size: 436.0 B

## `docker:1.11.2-git`

```console
$ docker pull docker@sha256:99168dd6df6c84811ad3e449552757c0679f6ba6887841ae8db2e5f64855bd8b
```

-	Platforms:
	-	linux; amd64

### `docker:1.11.2-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **32.8 MB (32811887 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:87db9acc91f713cb49c1a5b90063ef94421e0c3eb878922552c0dbcb5f233536`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:17:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:1d7e81cdc08bf6db6ce70280f4a26fd660b07f70e97802ee414af0155f46a3ea`  
		Last Modified: Thu, 23 Jun 2016 22:17:47 GMT  
		Size: 9.1 MB (9138421 bytes)

## `docker:1.11-git`

```console
$ docker pull docker@sha256:99168dd6df6c84811ad3e449552757c0679f6ba6887841ae8db2e5f64855bd8b
```

-	Platforms:
	-	linux; amd64

### `docker:1.11-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **32.8 MB (32811887 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:87db9acc91f713cb49c1a5b90063ef94421e0c3eb878922552c0dbcb5f233536`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:17:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:1d7e81cdc08bf6db6ce70280f4a26fd660b07f70e97802ee414af0155f46a3ea`  
		Last Modified: Thu, 23 Jun 2016 22:17:47 GMT  
		Size: 9.1 MB (9138421 bytes)

## `docker:1-git`

```console
$ docker pull docker@sha256:99168dd6df6c84811ad3e449552757c0679f6ba6887841ae8db2e5f64855bd8b
```

-	Platforms:
	-	linux; amd64

### `docker:1-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **32.8 MB (32811887 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:87db9acc91f713cb49c1a5b90063ef94421e0c3eb878922552c0dbcb5f233536`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:17:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:1d7e81cdc08bf6db6ce70280f4a26fd660b07f70e97802ee414af0155f46a3ea`  
		Last Modified: Thu, 23 Jun 2016 22:17:47 GMT  
		Size: 9.1 MB (9138421 bytes)

## `docker:git`

```console
$ docker pull docker@sha256:99168dd6df6c84811ad3e449552757c0679f6ba6887841ae8db2e5f64855bd8b
```

-	Platforms:
	-	linux; amd64

### `docker:git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **32.8 MB (32811887 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:87db9acc91f713cb49c1a5b90063ef94421e0c3eb878922552c0dbcb5f233536`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_VERSION=1.11.2
# Thu, 23 Jun 2016 20:18:27 GMT
ENV DOCKER_SHA256=8c2e0c35e3cda11706f54b2d46c2521a6e9026a7b13c7d4b8ae1f3a706fc55e1
# Thu, 23 Jun 2016 20:18:31 GMT
RUN set -x 	&& curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION.tgz" -o docker.tgz 	&& echo "${DOCKER_SHA256} *docker.tgz" | sha256sum -c - 	&& tar -xzvf docker.tgz 	&& mv docker/* /usr/local/bin/ 	&& rmdir docker 	&& rm docker.tgz 	&& docker -v
# Thu, 23 Jun 2016 20:18:32 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:18:33 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:18:33 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:17:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:10fb2f450fdc80d99e84f607c24917360bdbf360fe7329867de8322425c22624`  
		Last Modified: Thu, 23 Jun 2016 20:18:53 GMT  
		Size: 20.4 MB (20449706 bytes)
	-	`sha256:81ca7ec69872bf4ff8a3ffb899d32ff46a9e5eec6fc69aed7ad580552d3ffa02`  
		Last Modified: Thu, 23 Jun 2016 20:18:41 GMT  
		Size: 466.0 B
	-	`sha256:1d7e81cdc08bf6db6ce70280f4a26fd660b07f70e97802ee414af0155f46a3ea`  
		Last Modified: Thu, 23 Jun 2016 22:17:47 GMT  
		Size: 9.1 MB (9138421 bytes)

## `docker:1.10.3`

```console
$ docker pull docker@sha256:d9a95422aa236f1b09a96f1b044f87fe24934f5e29e7e877796dc242d98c4895
```

-	Platforms:
	-	linux; amd64

### `docker:1.10.3` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **13.1 MB (13085406 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:ae9ef03aa99cc5b0df11d5d4587675c680a76f30c35265ac5cff643b34533b27`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B

## `docker:1.10`

```console
$ docker pull docker@sha256:d9a95422aa236f1b09a96f1b044f87fe24934f5e29e7e877796dc242d98c4895
```

-	Platforms:
	-	linux; amd64

### `docker:1.10` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **13.1 MB (13085406 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:ae9ef03aa99cc5b0df11d5d4587675c680a76f30c35265ac5cff643b34533b27`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B

## `docker:1.10.3-dind`

```console
$ docker pull docker@sha256:a99b22b4c59dc9ec2a994323f10a973a03f81c0aa7547e7d8ee5cce2c98286ef
```

-	Platforms:
	-	linux; amd64

### `docker:1.10.3-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **15.2 MB (15175220 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:305c151749f493770562e91ff785683db8d0d38bef5206314f8de8c402523cd7`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:18:18 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:50 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:51 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:52 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:52 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:53 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:53 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:53 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:54 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B
	-	`sha256:7b47b276b6797dce30f9140d5e08e578583d7bd172fba57a8221594bb24a62b2`  
		Last Modified: Thu, 23 Jun 2016 22:18:30 GMT  
		Size: 2.1 MB (2065035 bytes)
	-	`sha256:caf8722f9b381318811d102f0ec3f74ebbbd6d4b51afa4ff11002f1c316610a1`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 22.5 KB (22521 bytes)
	-	`sha256:f3c5265cc84395db29a6f39082e848942bb35e5707c42ccac758c6fc245f1147`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:c3df17f3e669ec9de04d4ec42cae176f191d0e936f18455f6ebaa0001d8db27f`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 437.0 B

## `docker:1.10-dind`

```console
$ docker pull docker@sha256:a99b22b4c59dc9ec2a994323f10a973a03f81c0aa7547e7d8ee5cce2c98286ef
```

-	Platforms:
	-	linux; amd64

### `docker:1.10-dind` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **15.2 MB (15175220 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:305c151749f493770562e91ff785683db8d0d38bef5206314f8de8c402523cd7`
-	Entrypoint: `["dockerd-entrypoint.sh"]`
-	Default Command: `[]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:18:18 GMT
RUN apk add --no-cache 		btrfs-progs 		e2fsprogs 		e2fsprogs-extra 		iptables 		xfsprogs 		xz
# Fri, 01 Jul 2016 19:20:50 GMT
RUN set -x 	&& addgroup -S dockremap 	&& adduser -S -G dockremap dockremap 	&& echo 'dockremap:165536:65536' >> /etc/subuid 	&& echo 'dockremap:165536:65536' >> /etc/subgid
# Fri, 01 Jul 2016 19:20:51 GMT
ENV DIND_COMMIT=3b5fac462d21ca164b3778647420016315289034
# Fri, 01 Jul 2016 19:20:52 GMT
RUN wget "https://raw.githubusercontent.com/docker/docker/${DIND_COMMIT}/hack/dind" -O /usr/local/bin/dind 	&& chmod +x /usr/local/bin/dind
# Fri, 01 Jul 2016 19:20:52 GMT
COPY file:a00ae81495fdf69e63bb25e3b665aa29cb53cfe5788e6134adfc0f35caff6295 in /usr/local/bin/
# Fri, 01 Jul 2016 19:20:53 GMT
VOLUME [/var/lib/docker]
# Fri, 01 Jul 2016 19:20:53 GMT
EXPOSE 2375/tcp
# Fri, 01 Jul 2016 19:20:53 GMT
ENTRYPOINT &{["dockerd-entrypoint.sh"]}
# Fri, 01 Jul 2016 19:20:54 GMT
CMD []
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B
	-	`sha256:7b47b276b6797dce30f9140d5e08e578583d7bd172fba57a8221594bb24a62b2`  
		Last Modified: Thu, 23 Jun 2016 22:18:30 GMT  
		Size: 2.1 MB (2065035 bytes)
	-	`sha256:caf8722f9b381318811d102f0ec3f74ebbbd6d4b51afa4ff11002f1c316610a1`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 22.5 KB (22521 bytes)
	-	`sha256:f3c5265cc84395db29a6f39082e848942bb35e5707c42ccac758c6fc245f1147`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 1.8 KB (1821 bytes)
	-	`sha256:c3df17f3e669ec9de04d4ec42cae176f191d0e936f18455f6ebaa0001d8db27f`  
		Last Modified: Fri, 01 Jul 2016 19:24:12 GMT  
		Size: 437.0 B

## `docker:1.10.3-git`

```console
$ docker pull docker@sha256:97eacdd4c79a1e329c75b0a461f47cc28095a5ce3867169709d8008cf150471e
```

-	Platforms:
	-	linux; amd64

### `docker:1.10.3-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **22.2 MB (22223839 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:df8adc85261e85f28a4f150e7efc53f8debb60924b9fb0f98404293d1596ede2`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:45:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B
	-	`sha256:d106bc5d437fb68df4b8fdd791c90f635fa9c6727e6fd22887a5200a9dd62430`  
		Last Modified: Fri, 01 Jul 2016 19:24:37 GMT  
		Size: 9.1 MB (9138433 bytes)

## `docker:1.10-git`

```console
$ docker pull docker@sha256:97eacdd4c79a1e329c75b0a461f47cc28095a5ce3867169709d8008cf150471e
```

-	Platforms:
	-	linux; amd64

### `docker:1.10-git` - linux; amd64

-	Docker Version: 1.10.3
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **22.2 MB (22223839 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:df8adc85261e85f28a4f150e7efc53f8debb60924b9fb0f98404293d1596ede2`
-	Entrypoint: `["docker-entrypoint.sh"]`
-	Default Command: `["sh"]`

```dockerfile
# Thu, 23 Jun 2016 19:55:18 GMT
ADD file:852e9d0cb9d906535af512a89339fc70b2873a0f94defbcbe41cd44942dd6ac8 in /
# Thu, 23 Jun 2016 20:17:11 GMT
RUN apk add --no-cache 		ca-certificates 		curl 		openssl
# Thu, 23 Jun 2016 20:18:26 GMT
ENV DOCKER_BUCKET=get.docker.com
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_VERSION=1.10.3
# Thu, 23 Jun 2016 20:19:26 GMT
ENV DOCKER_SHA256=d0df512afa109006a450f41873634951e19ddabf8c7bd419caeb5a526032d86d
# Thu, 23 Jun 2016 20:19:30 GMT
RUN curl -fSL "https://${DOCKER_BUCKET}/builds/Linux/x86_64/docker-$DOCKER_VERSION" -o /usr/local/bin/docker 	&& echo "${DOCKER_SHA256}  /usr/local/bin/docker" | sha256sum -c - 	&& chmod +x /usr/local/bin/docker
# Thu, 23 Jun 2016 20:19:31 GMT
COPY file:50006c902e7677711aeffe4ab7b7042d649618b96dec760f322a8566dd83ab25 in /usr/local/bin/
# Thu, 23 Jun 2016 20:19:32 GMT
ENTRYPOINT &{["docker-entrypoint.sh"]}
# Thu, 23 Jun 2016 20:19:32 GMT
CMD ["sh"]
# Thu, 23 Jun 2016 22:45:38 GMT
RUN apk add --no-cache 		git 		openssh-client
```

-	Layers:
	-	`sha256:e110a4a1794126ef308a49f2d65785af2f25538f06700721aad8283b81fdfa58`  
		Last Modified: Thu, 23 Jun 2016 19:56:16 GMT  
		Size: 2.3 MB (2310286 bytes)
	-	`sha256:49e2842bdfdf9757b6fb042a914386833eb89594a0f6643fc8a7ca8e925dd58c`  
		Last Modified: Thu, 23 Jun 2016 20:17:29 GMT  
		Size: 913.0 KB (913008 bytes)
	-	`sha256:26e60b21b458c4944093a6f68c74a2b2337feba2c08f43a35cb7dcc1a4328e95`  
		Last Modified: Thu, 23 Jun 2016 20:19:46 GMT  
		Size: 9.9 MB (9861648 bytes)
	-	`sha256:ec51c463b77409ebba95c9468b16bbd827179ab223311226feb2219be06dcda4`  
		Last Modified: Thu, 23 Jun 2016 20:19:40 GMT  
		Size: 464.0 B
	-	`sha256:d106bc5d437fb68df4b8fdd791c90f635fa9c6727e6fd22887a5200a9dd62430`  
		Last Modified: Fri, 01 Jul 2016 19:24:37 GMT  
		Size: 9.1 MB (9138433 bytes)

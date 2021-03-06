<!-- THIS FILE IS GENERATED VIA './update-remote.sh' -->

# Tags of `eclipse-mosquitto`

-	[`eclipse-mosquitto:1.4.12`](#eclipse-mosquitto1412)
-	[`eclipse-mosquitto:latest`](#eclipse-mosquittolatest)

## `eclipse-mosquitto:1.4.12`

```console
$ docker pull eclipse-mosquitto@sha256:be16cbbde51c8fdcf090b6c7cce81c29570f40461bd227a641e631dfcfcca1a2
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `eclipse-mosquitto:1.4.12` - linux; amd64

```console
$ docker pull eclipse-mosquitto@sha256:561bf668026937497b443a3a3c31da4c271d3005ec19926154922eb2c43f3d91
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **2.2 MB (2166429 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:96f50276aa47b4aa553b312eaffd7111539c6fdac2893a5fbed2c5ac5a670c15`
-	Entrypoint: `["\/docker-entrypoint.sh"]`
-	Default Command: `["\/usr\/sbin\/mosquitto","-c","\/mosquitto\/config\/mosquitto.conf"]`

```dockerfile
# Fri, 03 Nov 2017 22:10:18 GMT
ADD file:1e87ff33d1b6765b793888cd50e01b2bd0dfe152b7dbb4048008bfc2658faea7 in / 
# Fri, 03 Nov 2017 22:10:18 GMT
CMD ["/bin/sh"]
# Sat, 04 Nov 2017 10:10:22 GMT
MAINTAINER David Audet <david.audet@ca.com>
# Sat, 04 Nov 2017 10:10:22 GMT
LABEL Description=Eclipse Mosquitto MQTT Broker
# Sat, 04 Nov 2017 10:10:26 GMT
RUN apk --no-cache add mosquitto=1.4.12-r0 &&     mkdir -p /mosquitto/config /mosquitto/data /mosquitto/log &&     cp /etc/mosquitto/mosquitto.conf /mosquitto/config &&     chown -R mosquitto:mosquitto /mosquitto
# Sat, 04 Nov 2017 10:10:26 GMT
COPY file:837d39cfa86d29b54b50c161745633f730844caea976da0ece1641e4e4b122aa in / 
# Sat, 04 Nov 2017 10:10:26 GMT
ENTRYPOINT ["/docker-entrypoint.sh"]
# Sat, 04 Nov 2017 10:10:27 GMT
CMD ["/usr/sbin/mosquitto" "-c" "/mosquitto/config/mosquitto.conf"]
```

-	Layers:
	-	`sha256:b56ae66c29370df48e7377c8f9baa744a3958058a766793f821dadcb144a4647`  
		Last Modified: Wed, 25 Oct 2017 23:21:25 GMT  
		Size: 2.0 MB (1991435 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:387ec854f55a56b1d1e4da41035b03004f215f35ab7aae838a37afe6d088b265`  
		Last Modified: Sat, 04 Nov 2017 10:10:34 GMT  
		Size: 174.8 KB (174850 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:ca1ace3097d2673b0ec539e1886521fc6d034b3c88d8c7faaa7a31fe9cd4b35d`  
		Last Modified: Sat, 04 Nov 2017 10:10:34 GMT  
		Size: 144.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip

## `eclipse-mosquitto:latest`

```console
$ docker pull eclipse-mosquitto@sha256:be16cbbde51c8fdcf090b6c7cce81c29570f40461bd227a641e631dfcfcca1a2
```

-	Manifest MIME: `application/vnd.docker.distribution.manifest.list.v2+json`
-	Platforms:
	-	linux; amd64

### `eclipse-mosquitto:latest` - linux; amd64

```console
$ docker pull eclipse-mosquitto@sha256:561bf668026937497b443a3a3c31da4c271d3005ec19926154922eb2c43f3d91
```

-	Docker Version: 17.06.2-ce
-	Manifest MIME: `application/vnd.docker.distribution.manifest.v2+json`
-	Total Size: **2.2 MB (2166429 bytes)**  
	(compressed transfer size, not on-disk size)
-	Image ID: `sha256:96f50276aa47b4aa553b312eaffd7111539c6fdac2893a5fbed2c5ac5a670c15`
-	Entrypoint: `["\/docker-entrypoint.sh"]`
-	Default Command: `["\/usr\/sbin\/mosquitto","-c","\/mosquitto\/config\/mosquitto.conf"]`

```dockerfile
# Fri, 03 Nov 2017 22:10:18 GMT
ADD file:1e87ff33d1b6765b793888cd50e01b2bd0dfe152b7dbb4048008bfc2658faea7 in / 
# Fri, 03 Nov 2017 22:10:18 GMT
CMD ["/bin/sh"]
# Sat, 04 Nov 2017 10:10:22 GMT
MAINTAINER David Audet <david.audet@ca.com>
# Sat, 04 Nov 2017 10:10:22 GMT
LABEL Description=Eclipse Mosquitto MQTT Broker
# Sat, 04 Nov 2017 10:10:26 GMT
RUN apk --no-cache add mosquitto=1.4.12-r0 &&     mkdir -p /mosquitto/config /mosquitto/data /mosquitto/log &&     cp /etc/mosquitto/mosquitto.conf /mosquitto/config &&     chown -R mosquitto:mosquitto /mosquitto
# Sat, 04 Nov 2017 10:10:26 GMT
COPY file:837d39cfa86d29b54b50c161745633f730844caea976da0ece1641e4e4b122aa in / 
# Sat, 04 Nov 2017 10:10:26 GMT
ENTRYPOINT ["/docker-entrypoint.sh"]
# Sat, 04 Nov 2017 10:10:27 GMT
CMD ["/usr/sbin/mosquitto" "-c" "/mosquitto/config/mosquitto.conf"]
```

-	Layers:
	-	`sha256:b56ae66c29370df48e7377c8f9baa744a3958058a766793f821dadcb144a4647`  
		Last Modified: Wed, 25 Oct 2017 23:21:25 GMT  
		Size: 2.0 MB (1991435 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:387ec854f55a56b1d1e4da41035b03004f215f35ab7aae838a37afe6d088b265`  
		Last Modified: Sat, 04 Nov 2017 10:10:34 GMT  
		Size: 174.8 KB (174850 bytes)  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip
	-	`sha256:ca1ace3097d2673b0ec539e1886521fc6d034b3c88d8c7faaa7a31fe9cd4b35d`  
		Last Modified: Sat, 04 Nov 2017 10:10:34 GMT  
		Size: 144.0 B  
		MIME: application/vnd.docker.image.rootfs.diff.tar.gzip

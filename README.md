[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/artforge-rtranslate.svg)](https://hub.docker.com/r/rubygem/artforge-rtranslate/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/artforge-rtranslate.svg)](https://hub.docker.com/r/rubygem/artforge-rtranslate/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/artforge-rtranslate.svg)](https://hub.docker.com/r/rubygem/artforge-rtranslate/)
[![Gem Downloads](https://img.shields.io/gem/dt/artforge-rtranslate.svg)](https://rubygems.org/gems/artforge-rtranslate/)
# artforge-rtranslate

Auto-Generated Docker image for artforge-rtranslate to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/artforge-rtranslate`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/artforge-rtranslate`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/artforge-rtranslate`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/artforge-rtranslate/)

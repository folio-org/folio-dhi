# folio-dhi

Copyright (C) 2026 The Open Library Foundation

This software is distributed under the terms of the Apache License,
Version 2.0. See the file "[LICENSE](LICENSE)" for more information.

## Introduction

Mirror selected images from [dhi.io](https://hub.docker.com/hardened-images/catalog)
to [docker.io/folioci](https://hub.docker.com/u/folioci).

Downloading images from dhi.io requires a docker login, while downloading
from our mirror doesn't. This simplifies development setup and build pipelines.

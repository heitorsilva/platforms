# Copyright 2015 tsuru authors. All rights reserved.
# Use of this source code is governed by a BSD-style
# license that can be found in the LICENSE file.

FROM	tsuru/base-platform
ADD	. /var/lib/tsuru/elixir
RUN	cp /var/lib/tsuru/elixir/deploy /var/lib/tsuru
RUN	/var/lib/tsuru/elixir/install

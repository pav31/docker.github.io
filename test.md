---
description: Smoketest page
title: Testing page
hide_from_sitemap: true
---

# Heading 1

Plain block of text.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu
fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
culpa qui officia deserunt mollit anim id est laborum.

## Heading 2

> **Note**: This is the highest heading included in the right-nav.
> To include more heading levels, set `toc_min: 1` in the page-s front-matter.
> You can go all the way to 6, but if `toc_min` is geater than `toc_max` then
> no headings will show.

Text with various styles, basic markdown formatting. You should **not** see a single line comment below this line.

<!-- This is a comment. You should not see it rendered in the page. -->

Once you create or link to a repository in Docker Cloud, you can set up [automated testing](/docker-cloud/builds/automated-testing.md) and [automated builds](/docker-cloud/builds/automated-build.md).

![a small cute image](/images/footer_moby_icon.png)

> **Note**: This is a note. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam.

![a pretty wide image](/images/banner_image_24512.png)

<center>
This line is centered with HTML.
</center>

This line is centered with curly-brace injection.
{: style="text-align:center" }

Some Lorem ipsum text with formatting and styling.

**Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt** ut labore `et dolore magna aliqua`. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo _consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore_ eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt _**in culpa quiofficia deserunt mollit anim id est laborum.**_


### Heading 3

> **Note**: This is the lowest heading included in the right-nav, by default.
> To include more heading levels, set `toc_max: 4` in the page's front-matter.
> You can go all the way to 6.

A selection of lists, ordered and unordered, with indented sub elements.

> **Note**: This is some note text.

1. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

   > **Note**: This is indented note text with followon image

   ![a small cute image](/images/footer_moby_icon.png)

2. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

    1. A second level ordered list
       1. A third level ordered list
       2. A second third level ordered list
       3. A second third level ordered list

    2. A second second level ordered list.

       > **Tip**: this is doubly indented note text

    3. A third second level ordered list.

       ```
       with code block
       ```

3. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

   ![a small cute image](/images/footer_moby_icon.png)

4. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.
5. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

    * A second level unordered list.

      * A third level unordered list.

        * A fourth level unordered list.
        * A second line of fourth level unordered list.
        * A third line of fourth level unordered list.

      * A second line of third level unordered list.
      * A third line of third level unordered list.

    * A second second level unordered list.

       > **Note**: this is indented note text

    * A third second level unordered list.

      ```
      with codeblock
      ```

6. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.
7. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua. eu fugiat nulla pariatur.
8. Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
tempor incididunt ut labore et dolore magna aliqua.

   ![a pretty wide image](/images/banner_image_24512.png)

9. proident, sunt in culpa qui
10. officia deserunt mollit anim id

    ```none
    This is unstyled (none) text. This tells us if the Kramdown gotcha about indenting the exact number of spaces works or not.
    ```
11. est laborum.
12. And another line, because reasons.


> **Well**: This is a Note block with a nested code block in it.
>
> ```json
> "server": {
>   "http_addr": ":4443",
>   "tls_key_file": "./fixtures/notary-server.key",
>   "tls_cert_file": "./fixtures/notary-server.crt"
> }
> ```

#### Heading 4

Some tables in markdown and html.

| Permission level | Access |
| ------------- | ------------- |
| **Subheading (boring old bold styling)** | |
| Read | Pull |
| Read/Write | Pull, push |
| Admin | All of the above, plus update description, create and delete |

If you need block-level HTML within your table cells, such as multiple
paragraphs, lists, sub-tables, etc, then you need to make a HTML table.
This is also the case if you need to use rowspans or colspans. Try to avoid
setting styles directly on your tables! If you set the width on a `<td>`, you
only need to do it on the first one. If you have a `<th>`, set it there.

<table>
  <tr>
    <th "width="50%">Left channel</th>
    <th>Right channel</th>
  </tr>
  <tr>
    <td>This is some test text. <br><br>This is more text on a new line. <br><br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
    </td>
    <td>This is some more text about the right hand side. There is a <a href="https://github.com/docker/docker/tree/master/experimental" target="_blank" class="_">link here to the Docker Experimental Features README</a> on GitHub.<br><br>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</td>
  </tr>
  <tr>
  <td>
  <a class="button outline-btn" href="/">Go to the docs!</a><br><br>
  <a href="/"><font color="#BDBDBD" size="-1">It is dark here. You are likely to be eaten by a grue.</font></a>
  </td>
  <td>
  <a class="button outline-btn" href="/">Go to the docs!</a><br><br>
  <a href="/"><font color="#BDBDBD" size="-1">It is dark here. You are likely to be eaten by a grue.</font></a>
  </td>
  </tr>
</table>

##### Heading 5

This heading is not included in the right-nav. To include it set `toc_max: 5` in
the page's front-matter.

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.

###### Heading 6?!

This heading is not included in the right-nav. To include it set `toc_max: 6` in
the page's front-matter.

Probably not the most useful thing, but nice to know it exists.

## Some code block samples

#### Rawstyle

```none
none with raw
{% raw %}
$ some command with {{double braces}}
$ some other command
{% endraw %}
```

```bash
bash with raw
{% raw %}
$ some command with {{double braces}}
$ some other command
{% endraw %}
```

#### Bash

```bash
$ echo "deb https://packages.docker.com/1.12/apt/repo ubuntu-trusty main" | sudo tee /etc/apt/sources.list.d/docker.list
```

#### GO

```go
incoming := map[string]interface{}{
    "asdf": 1,
    "qwer": []interface{}{},
    "zxcv": []interface{}{
        map[string]interface{}{},
        true,
        int(1e9),
        "tyui",
    },
}

canonical, err := json.Marshal(incoming)
if err != nil {
  // ... handle error
}
```

#### Python

```python
return html.format(name=os.getenv('NAME', "world"), hostname=socket.gethostname(), visits=visits)
```

#### Ruby

```ruby
docker_service 'default' do
  action [:create, :start]
end

docker_image 'busybox' do
  action :pull
end

docker_container 'an echo server' do
  repo 'busybox'
  port '1234:1234'
  command "nc -ll -p 1234 -e /bin/cat"
end
```

#### JSON

```json
"server": {
  "http_addr": ":4443",
  "tls_key_file": "./fixtures/notary-server.key",
  "tls_cert_file": "./fixtures/notary-server.crt"
}
```

#### HTML

```html
<!DOCTYPE html>
<html>
<head>
<title>Welcome to nginx!</title>
</head>
</html>
```

#### Markdown

```md
[![Deploy to Docker Cloud](https://files.cloud.docker.com/images/deploy-to-dockercloud.svg)](https://cloud.docker.com/stack/deploy/?repo=<repo_url>)
```

#### ini

```ini
[supervisord]
nodaemon=true

[program:sshd]
command=/usr/sbin/sshd -D

[program:apache2]
command=/bin/bash -c "source /etc/apache2/envvars && exec /usr/sbin/apache2 -DFOREGROUND"
```

#### Dockerfile

```dockerfile
#
# example Dockerfile for https://docs.docker.com/examples/postgresql_service/
#

FROM ubuntu

# Add the PostgreSQL PGP key to verify their Debian packages.
# It should be the same key as https://www.postgresql.org/media/keys/ACCC4CF8.asc
RUN apt-key adv --keyserver hkp://p80.pool.sks-keyservers.net:80 --recv-keys B97B0AFCAA1A47F044F244A07FCC7D46ACCC4CF8

# Add PostgreSQL's repository. It contains the most recent stable release
#     of PostgreSQL, ``9.3``.
RUN echo "deb http://apt.postgresql.org/pub/repos/apt/ precise-pgdg main" > /etc/apt/sources.list.d/pgdg.list

# Install ``python-software-properties``, ``software-properties-common`` and PostgreSQL 9.3
#  There are some warnings (in red) that show up during the build. You can hide
#  them by prefixing each apt-get statement with DEBIAN_FRONTEND=noninteractive
RUN apt-get update && apt-get install -y python-software-properties software-properties-common postgresql-9.3 postgresql-client-9.3 postgresql-contrib-9.3

# Note: The official Debian and Ubuntu images automatically ``apt-get clean``
# after each ``apt-get``

# Run the rest of the commands as the ``postgres`` user created by the ``postgres-9.3`` package when it was ``apt-get installed``
USER postgres

# Create a PostgreSQL role named ``docker`` with ``docker`` as the password and
# then create a database `docker` owned by the ``docker`` role.
# Note: here we use ``&&\`` to run commands one after the other - the ``\``
#       allows the RUN command to span multiple lines.
RUN    /etc/init.d/postgresql start &&\
    psql --command "CREATE USER docker WITH SUPERUSER PASSWORD 'docker';" &&\
    createdb -O docker docker

# Adjust PostgreSQL configuration so that remote connections to the
# database are possible.
RUN echo "host all  all    0.0.0.0/0  md5" >> /etc/postgresql/9.3/main/pg_hba.conf

# And add ``listen_addresses`` to ``/etc/postgresql/9.3/main/postgresql.conf``
RUN echo "listen_addresses='*'" >> /etc/postgresql/9.3/main/postgresql.conf

# Expose the PostgreSQL port
EXPOSE 5432

# Add VOLUMEs to allow backup of config, logs and databases
VOLUME  ["/etc/postgresql", "/var/log/postgresql", "/var/lib/postgresql"]

# Set the default command to run when starting the container
CMD ["/usr/lib/postgresql/9.3/bin/postgres", "-D", "/var/lib/postgresql/9.3/main", "-c", "config_file=/etc/postgresql/9.3/main/postgresql.conf"]
```

#### YAML

```yaml
authorizedkeys:
  image: dockercloud/authorizedkeys
  deployment_strategy: every_node
  autodestroy: always
  environment:
    - AUTHORIZED_KEYS=ssh-rsa AAAAB3Nsomelongsshkeystringhereu9UzQbVKy9o00NqXa5jkmZ9Yd0BJBjFmb3WwUR8sJWZVTPFL
  volumes:
    /root:/user:rw
```

## Admonitions

> **Note**: This is a note.

> **Info**: This is an info.

> **Tip**: This is a tip.

> **Warning**: This is a warning.

> **Caution**: This is a caution.

> **Note**: One line of note text
> another line of note text

> **Note**: This is a note with a list and a table in it.
>
> - List item 1
> - List item 2
>
> |Table column 1 | Table column 2 |
> |---------------|----------------|
> | Row 1 column 1 | Row 2 column 2 |
> | Row 2 column 1 | Row 2 column 2 |
>
> And another sentence to top it all off.

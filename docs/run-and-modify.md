# Run & Modify

## Run the container

from the project root, the location where the docker-compose files exists:

```text
docker-compose up -d
```

## Enter the container

```text
docker exec -u root -it <containername> /bin/bash
```

## Inside the container

Navigate into:

```text
/usr/lib/python3/dist-packages
```

and install pandas or other python packages:

```text
pip3 install pandas
```

exit the container

```text
exit
```

## Addons

If you wish you can install addons before creating the container, although this will likely lead to failures.


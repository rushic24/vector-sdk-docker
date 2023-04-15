## Usage

Here are some example snippets to help you get started creating a container.

```
cd sdk-0.6.0
docker-compose up -d
```

## How to generate configs

If you already have config files, you can just provide those files via anki_vector folder. 
If you have not, just follow the list.

1. Run container with docker compose
2. Run `docker exec -it vector.sdk python -m anki_vector.configure`
3. Follow the setup wizard
4. Find `sdk_config.ini` and `Vector-XXXX-XXXXXXXX.cert` in `anki_vector` folder


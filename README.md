# Install

Copy contain from [Google Sheets](https://docs.google.com/spreadsheets/d/1zXfWhqvryw3gPjpTF1YzO1ABTxaOR-3-VoPP4jyfPmM/edit?gid=1655021133#gid=1655021133&range=B5)


# Set variables to system

```bash
sudo nano /etc/profile.d/omni_env.sh
# Past vars to here
sudo chmod +x /etc/profile.d/omni_env.sh
```
Restart system

# Check result

```bash
printenv
echo $<var name>
```

# Start docker
```bash
docker-compose up -d
```

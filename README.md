APT repository for slay-port

## Usage
```bash
curl -fsSL https://hammadxcm.github.io/apt-repo/KEY.gpg | sudo gpg --dearmor -o /usr/share/keyrings/slay-port.gpg
echo "deb [signed-by=/usr/share/keyrings/slay-port.gpg] https://hammadxcm.github.io/apt-repo stable main" | sudo tee /etc/apt/sources.list.d/slay-port.list
sudo apt update && sudo apt install slay-port
```

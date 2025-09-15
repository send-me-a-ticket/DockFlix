# DockFlix
#### Movies, Music, Shows and more for minimum cost.
#### Leverage Proton VPN free tier for security and privacy.
#### Stream popular media on user demand.

<br><br>
## Prequisite

1. Docker should be installed.
<br>&emsp;&emsp; Windows [Link](https://apps.microsoft.com/detail/xp8cbj40xlbwkx)
<br>&emsp;&emsp; Linux [Link](https://github.com/docker/docker-install)
<br>&emsp;&emsp; MacOS [Link](https://formulae.brew.sh/formula/docker)

3. Create or use ProtonVPN Account.
<br>&emsp;&emsp; Get VPN configuration file: [account.protonvpn.com/downloads](https://account.protonvpn.com/downloads)
4. Update `mediaserver.env` file to include the `.conf` values from `Step 2`.

<br><br>
## Install

Option 1: Run in terminal after navigating to downloaded src path - <br>
```docker compose -f ./mediaserver.yaml --env-file ./mediaserver.env up -d```

Option 2: Run in Portainer
1. Create a new stack, copy contents from `mediaserver.yaml`
2. Create ENV entries from `mediaserver.env`


<br><br>
## Usage

Once setup, access ports from 8000-8010 to access each component of the service.

[8001](http://127.0.0.1:8001) - Baz <br>
[8002](http://127.0.0.1:8002)  - Hom <br>
[8003](http://127.0.0.1:8003)  - Lid <br>
[8004](http://127.0.0.1:8004)  - Prowl <br>
[8005](http://127.0.0.1:8005)  - Rad <br>
[8006](http://127.0.0.1:8006)  - Son <br>
[8007](http://127.0.0.1:8007)  - Stash <br>
[8008](http://127.0.0.1:8008)  - qBT <br>
[8009](http://127.0.0.1:8009)  - Jellyfin <br>
[8010](http://127.0.0.1:8010)  - JellySeer

Now, you can setup connections between different tools to each other. Recommended to use hostname `host.docker.internal` when configuring connections between different tools.



<br><br>
## Disclaimer

THIS SOFTWARE IS PROVIDED AS IS AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL DONALD TRUMP BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

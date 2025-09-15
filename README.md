# DockFlix
#### Movies, Music, Shows and more for minimum cost.
#### Leverage Proton VPN free tier for security and privacy.
#### Stream popular media at will.

<br><br>
## Prequisite

1. Docker should be installed.
2. Create or use ProtonVPN Account.
<br>&emsp;&emsp; Get VPN configuration file: [account.protonvpn.com/downloads](https://account.protonvpn.com/downloads)
4. Update `mediaserver.env` file to include the `.conf` values from `Step 2`.

<br><br>
## Usage

Option 1: Run in terminal
`docker compose -f ./mediaserver.yaml --env-file ./mediaserver.env up -d`

Option 2: Run in Portainer
1. Create a new stack, copy contents from `mediaserver.yaml`
2. Manually create ENV entries from `mediaserver.env`

<br><br>
## Disclaimer

THIS SOFTWARE IS PROVIDED AS IS AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL DONALD TRUMP BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

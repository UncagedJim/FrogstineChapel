# Local Data Exchange

Check the wiki for more information

# Update the list of known devices

The message from the device is digitaly signed, you need to edit the config file */config/default.json* to match the "Secret" for each of them. 

```json
{
  "KnowSources": [
    {"source": "SCA_rVYGiME5tYrf", "secret": "FGQEEESSA"},
    {"source": "SWS_rVYGiME5tYrf", "secret": "FGQEEESSA"},

    ..... 
  ]
} 
```

# Run the Server

To run this sample type this commands into a shell

```node
npm install
npm start
```

*NodeJS need to be installed on the machine*

*The settings on your SWS or SCA will need configuring to where the infomation is sent. An example string is below where the "IPaddress" is the location of the server.*
```
 http://"IPaddress":7878/localexchange/endpoint
```
# Terms of Use

_THE SAMPLE CODE IS PROVIDED “AS IS” AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL PAGERDUTY OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) SUSTAINED BY YOU OR A THIRD PARTY, HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT ARISING IN ANY WAY OUT OF THE USE OF THIS SAMPLE CODE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE._

_The Code is not covered by any Seneye Service Level Agreements._
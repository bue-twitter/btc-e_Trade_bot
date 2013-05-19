BTC-e Trade bot
===============

Uses alanmcintyre's btc-e api to automatically buy/sell a chosen currency from btc-e.
found at: https://github.com/alanmcintyre/btce-api

Cloning
-------

To clone the bot, you must clone with recursion i.e:
    
    git clone --recursive https://github.com/mcfundash/btc-e_Trade_bot.git

### Usage

To use the bot, just put your api key and secret into api_key and api_secret in auto.py, then run it with python 2.7
also trading pair may be selected (ltc_btc used by defualt). Just edit pair, and curr1 and curr2.
example:
    
    pair = "ltc_usd"
    curr1 = "balance_ltc"
    curr2 = "balance_usd"

Also you may edit other variables such as trade threshold
### Donate

If you like my bot, a donation to either one of the following addresses  would be appreciated:

    LTC:  LNNBkSyEDQZnUwV9E5GYA9eGTUrJ1zwDLS
    BTC:  19WRmGTX417vzAu2bv65QicNj54QMVn1qF

### Legal

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

<b>I have ALSO cloned this script for harm reduction purposes. This is taken from felinegamblers script, in which she alegedly placed backdoors into, along with the CoinDice script.
<br>
I know that this script was originally a paid script, and this is not an attempt to undermine the original developers work and effort. In reality, people will use the script no matter what, and a lot will get burned because of malicious people. 
<br>
So, I will work on cleaning this for those that can't afford 1.1BTC and will use a free script regardless. Getting funds stolen is never fun, and nobody should ever have to endure that, even if the script is ...pirated?..</b>

<br>

CryptoBlackJack is a popular CryptoCurrency BlackJack game, CryptoBlackJack is free to use and distribute.<br>
<br>
== Pre-Requisites ==<br>
Linux<br>
Apache2<br>
PHP<br>
MySQL<br>
bitcoind<br>
<br>
== Installation ==<br>
<br>
bitcoind<br>
<br>
1) Install bitcoind<br>
2) Edit your bitcoin.conf in ~/.bitcoin/bitcoin.conf (you may need to create this) to look like the following, You will need to change the username and pass.<br>
<br>
server=1<br>
rpcuser=bitcoinrpc<br>
rpcpassword=dfbufbSUBUSbf7763YSFYbfybsiyb87<br>
rpcport=8332<br>
<br>
3) run bitcoind -daemon<br>
4) let it fully sync to the network before moving on to the next part (or the script will not work)<br>
<br>
CryptoBlackJack<br>
<br>
1) install git (ubuntu: sudo apt-get install git)(fedora/redhat: sudo yum install git)<br>
2) Change to a directory of your choice and run the command (git clone https://github.com/felinegambler/CryptoBlackJack)<br>
3) Change to the inc/ directory and change the permissions to 777 (chmod 777 *)<br>
4) Run the script from your prefered web browser and follow the installation instructions on screen<br>
5) Once completed remove the install directory for security reasons<br>
6) You now have access to http://your-server/blackjack/admin (or wherever you put the blackjack script)<br>
7) Finally, Deposit your funds using the receiving address on the wallet tab in the admin menu<br>
<br>
if you have any problems you can contact me for installation help felinegambler@gmail.com<br>
<br>
Good Luck and have fun running your own casino!<br>

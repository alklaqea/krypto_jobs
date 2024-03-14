# krypto_jobs

You work at a startup that is building a new and disruptive platform called KryptoJobs2Go (a fictitious platform). KryptoJobs2Go is an application that its customers can use to find fintech professionals from among a list of candidates, hire them, and pay them. As KryptoJobs2Go’s lead developer, you have been tasked with integrating the Ethereum blockchain network into the application in order to enable your customers to instantly pay the fintech professionals whom they hire with cryptocurrency.

In this Challenge, you will complete the code that enables your customers to send cryptocurrency payments to fintech professionals. To develop the code and test it out, you will assume the perspective of a KryptoJobs2Go customer who is using the application to find a fintech professional and pay them for their work.

### What You're Creating

To complete this Challenge, you will use two Python files, both of which are contained in the starter folder.

The first file that you will use is called `krypto_jobs.py`. It contains the code associated with the web interface of your application. The code included in this file is compatible with the Streamlit library. You will write all of your code for this Challenge in this file.

The second file that you will use is called `crypto_wallet.py`. This file contains the Ethereum transaction functions that you have created throughout this module’s lessons. By using import statements, you will integrate the `crypto_wallet.py` Python script into the KryptoJobs2Go interface program that is found in the `krypto_jobs.py` file.

### Integrating these two files will allow you to automate the tasks associated with generating a digital wallet, accessing Ethereum account balances, and signing and sending transactions via a personal Ethereum blockchain called Ganache.

<br>
<br>

# How did it go?

We created 2 transactions. We hired lane and kendall but in this image, we will discuss kendall. Kendal charges 0.16 ETH per hour. We hired her for a total of 10 hours which costed us a total of 1.6 ETH. We went the transaction and we were able to get a validated transaction hash.
<br>
<br>
<br>


![alt text](<streamlit validated transaction.png>)

This is the public address of all my wallets. The address that was used to send the transactions ends with "E66A". We started with a balance of 100 ETH.
Kendall charges 0.16 ETH per hour and it costed us 1.6 ETH to hire her for 10 hours.
Lane charges 0.2 ETH per hour and it costed us a total of 1.6 ETH to hire her for 8 hours.  Which leaves us with a remaining balance of 96.8 ETH.
<br>
<br>
<br>



![alt text](<Ganache balance.png>) 
<br>
<br>
<br>


We used the same "FROM ADDRESS" but we used different "TO ADDRESS". The address ending in "BA45" belongs to Kendall The address ending in "29F0" belongs to Lane 
<br>
<br>
<br>
<br>
![alt text](<Ganache transactions.png>)
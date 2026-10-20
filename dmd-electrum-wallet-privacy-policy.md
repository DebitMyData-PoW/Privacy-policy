# DMD Electrum Wallet – Privacy Policy

Last updated: October 20, 2026

This privacy policy explains how DMD Electrum Wallet, the DebitMyData (DMD) wallet for Android published by the DebitMyData project, handles information when you use the app.

## 1. Summary

- DMD Electrum Wallet is a non-custodial wallet: your recovery phrase (seed), private keys and wallet files stay on your device.
- You do not need an account, email address or phone number to use the app.
- The app contains no advertising, analytics, tracking or third-party SDKs.
- To show your balance and send transactions, the app connects to DMD Electrum servers. These servers receive the information described in section 4.

## 2. Information we do not collect

- We do not collect your name, email address, phone number or other personal information.
- We do not collect your recovery phrase, private keys or wallet passwords. They never leave your device.
- We do not use cookies, analytics, advertising identifiers or crash-reporting services.
- We do not sell, rent or trade any information.

## 3. Information stored on your device

The app stores the following on your device only:

- your wallets, including your recovery phrase and private keys, encrypted with the wallet password you choose;
- your transaction history, address labels, the contacts you save in the app's address book, and app settings;
- a copy of DebitMyData block headers, used to verify transactions.

The app's data is excluded from Android's automatic cloud backup. Uninstalling the app deletes this data from your device. Keep your recovery phrase written down in a safe place: it is the only way to restore your funds.

## 4. Network connections

**DMD Electrum servers.** To show your balance and history and to send your transactions, the app connects to Electrum servers for the DebitMyData blockchain. By default it uses the servers run by the DebitMyData project (electrum01.debitmydata.network to electrum06.debitmydata.network). Like any internet server, these servers receive:

- your IP address;
- the wallet addresses the app asks about, so they can return their balances and transactions;
- the transactions you choose to send, which they relay to the DebitMyData network.

We use this information only to answer the app's requests and to operate and secure the servers. We do not use it to identify you, and we do not sell it or share it with third parties. Transactions sent to the DebitMyData network are public by nature: anyone can see them on the blockchain.

You can choose your own Electrum server, including one you run yourself, in the app's network settings. You can also connect through a proxy or Tor (for example with Orbot) to hide your IP address from the servers.

**Nostr Cosigner (optional, off by default).** If you turn on the Nostr Cosigner feature for multi-signature wallets, the app exchanges partially signed transactions with your co-signers through public Nostr relays run by third parties. These transactions are encrypted for your co-signers, but the relays receive your IP address. You can change the list of relays in the app's settings.

**Block explorer.** If you choose to open a transaction or address in the block explorer, it opens mempool.debitmydata.io in your web browser. That website receives your request like any website you visit.

The app does not contact any other service: exchange-rate lookups, automatic update checks and crash reports are disabled in this app.

## 5. Permissions

- **Internet:** to connect to Electrum servers, as described above.
- **Camera:** only to scan QR codes when you choose to. Camera images are processed on your device and are not stored or sent anywhere.
- **Biometrics (fingerprint or face unlock):** optional, to unlock the app. Biometric data is handled by Android itself; the app never receives it.
- **Notifications:** to tell you about incoming transactions.
- **Storage:** only when you choose to import or export files, such as wallet backups or transactions.

## 6. Google Play

If you install the app from Google Play, Google may collect information under its own privacy policy, such as installation statistics and crash reports from Android. We may see this information only in aggregated form in the Google Play Console.

## 7. Children's privacy

The app is not directed at children under 13, and we do not knowingly collect information from anyone, including children.

## 8. Security

Your funds are protected by your recovery phrase and wallet password, which only you hold. We recommend that you:

- protect your device with a screen lock;
- use a strong wallet password;
- keep your recovery phrase offline, in a safe place, and never share it with anyone. The DebitMyData team will never ask for it.

## 9. Your choices

Because we do not hold an account or personal profile for you, there is no personal data on our side to access, correct or delete. You control all data stored by the app, and you can delete it at any time by deleting your wallets or uninstalling the app.

## 10. Open source

DMD Electrum Wallet is open-source software based on Electrum (MIT license). Its source code is available at https://github.com/DebitMyData-PoW/electrum

## 11. Changes to this policy

We may update this privacy policy. Changes will be published on this page with a new "Last updated" date.

## 12. Contact

If you have questions about this privacy policy, contact us by email at [info@debitmydata.com](mailto:info@debitmydata.com).

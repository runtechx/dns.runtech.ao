# Android

Configure **dns.runtech.ao** on your Android device.



## Method 1 — Private DNS (DNS-over-TLS) ⭐ Recommended

Private DNS encrypts DNS queries between your device and **dns.runtech.ao** using DNS-over-TLS (DoT).

1. Open **Settings**.
2. Tap **Network & Internet**.
3. Tap **Private DNS**.
4. Select **Private DNS provider hostname**.
5. Enter:

```
dns.runtech.ao
```

6. Tap **Save**.

Your device will now use encrypted DNS whenever possible.



## Method 2 — Manual DNS

If your device does not support Private DNS, configure the DNS servers manually.

1. Open **Settings**.
2. Tap **Network & Internet**.
3. Tap **Wi-Fi**.
4. Select your connected Wi-Fi network.
5. Tap **Modify** or **Edit Network**.
6. Expand **Advanced options**.
7. Change **IP settings** to **Static**.
8. Configure the DNS servers:

| DNS Server | Address |
|------------|---------|
| Primary | `196.61.76.76` |
| Secondary | `102.213.34.98` |
| Tertiary (optional) | `95.216.191.135` |

9. Save the configuration.

Your Android device is now using **dns.runtech.ao**.

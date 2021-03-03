# privateRDP


Windows Server 2019 Github with RDP Access (ngrok AP)

Create a free VPS config 2cpu-7gb Ram FREE with Github:

- Click Fork screen right corner to save to your Github.
- Truy cập https://dashboard.ngrok.com để lấy NGROK_AUTH_TOKEN
- Ở Github vào Settings > Secrets > New repository secret

* Phần Name: điền NGROK_AUTH_TOKEN
* Phần Value: truy cập https://dashboard.ngrok.com/auth/your-authtoken Copy và Paste Your Authtoken vào

- Ấn Add secret
- Chuyển qua Action > CI > Run workflow
- Reload lại trang và ấn CI > build
- Ấn mũi tên xuống ở Connect To Your RPD để lấy IP, User, Password.

#### Cre: https://github.com/ThuongHai

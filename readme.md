# Bot giới thiệu tự động giao thức Naoris

Bot này tự động hóa quá trình tạo tài khoản và sử dụng mã giới thiệu cho Giao thức Naoris.

## Đặc trưng

- Tự động tạo ví ngẫu nhiên.
- Sử dụng proxy để tránh lệnh cấm IP.
- Sử dụng puppter để bypass cf.

## Yêu cầu

- Node.js v18.20.5 LTS hoặc mới nhất.
- npm (Trình quản lý gói nút)

## Cài đặt

1. Clone the repository:

   ```sh
   git clone https://github.com/anht3k52/naoris-autoref.git
   cd naoris-autoref
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

3. Create a `proxy.txt` file in the root directory and add your proxies (one per line)(Optional).

## Usage

1. Run the bot:

   ```sh
   node .
   ```

2. Follow the prompts to enter your referral code

## Output

- The created accounts will be saved in `accounts.txt` and `accounts.json`.

## Notes

- Make sure to use valid proxies to avoid IP bans.
- For now only tested on windows
- The bot will attempt to verify the email up to 5 times before giving up.

## Stay Connected

- Channel Telegram : [Telegram](https://t.me/samcvn)


This tool is for educational purposes only. Use it at your own risk.

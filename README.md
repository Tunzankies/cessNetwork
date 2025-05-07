# CESS Network Tool

Tool tự động hóa cho CESS Network với khả năng fake UserAgent (thông số thiết bị).

## Link Airdrop
https://cess.network/deshareairdrop/?code=9222341

## Cấu hình
File `config.json`:
```json
{
    "numberThread": 20,    // Số luồng chạy
    "waitTime": 10000,     // Thời gian delay sau mỗi lần chạy (ms)
    "checkProxy": true,    // Kiểm tra proxy còn hoạt động không
    "refCode": "9222341",  // Mã giới thiệu CESS Network
    "passwordMail": "Tunzankies@" // Mật khẩu tạo tài khoản buff ref
}
```

## Cấu trúc file dữ liệu

### 1. account.txt
Lưu thông tin tài khoản sau khi đăng ký theo định dạng: `mail|pass|ref_code`
```
VD: r4hkaj@chefalicious.com|Tunzankies@|8106070
```

### 2. OKX.txt
Lưu thông tin ví OKX theo định dạng: `address|privateKey`
```
VD: 0xc7....6ac8|0xa68....75fca
```

### 3. proxy.txt
Lưu thông tin proxy theo định dạng: `ip:port:user:pass`

### 4. token.txt
Lưu token đăng nhập để chạy task (tự động cập nhật)

## Chức năng chính

1. **Buff Reff** - Tự động tạo tài khoản và sử dụng mã giới thiệu
2. **Làm nhiệm vụ** - Tự động hoàn thành các nhiệm vụ trong CESS Network
3. **Kết nối OKX** - Kết nối ví OKX
4. **Lấy lại token** - Tự động lấy token mới khi hết hạn (token có hạn 3 giờ)
5. **Connect X** - Kết nối tài khoản X (đang phát triển)
   - Liên hệ mua tài khoản X: @tunankies (550đ/X)
6. **Thoát**

## Hỗ trợ
Liên hệ hỗ trợ: @tunankies 

---

# CESS Network Tool

Automation tool for CESS Network with UserAgent spoofing capability.

## Airdrop Link
https://cess.network/deshareairdrop/?code=9222341

## Configuration
File `config.json`:
```json
{
    "numberThread": 20,    // Number of threads
    "waitTime": 10000,     // Delay time after each run (ms)
    "checkProxy": true,    // Check if proxy is active
    "refCode": "9222341",  // CESS Network referral code
    "passwordMail": "Tunzankies@" // Password for creating buff ref account
}
```

## Data File Structure

### 1. account.txt
Stores account information after registration in the format: `mail|pass|ref_code`
```
Example: r4hkaj@chefalicious.com|Tunzankies@|8106070
```

### 2. OKX.txt
Stores OKX wallet information in the format: `address|privateKey`
```
Example: 0xc7....6ac8|0xa68....75fca
```

### 3. proxy.txt
Stores proxy information in the format: `ip:port:user:pass`

### 4. token.txt
Stores login token for running tasks (automatically updated)

## Main Features

1. **Buff Reff** - Automatically creates accounts and uses referral codes
2. **Complete Tasks** - Automatically completes tasks in CESS Network
3. **Connect OKX** - Connects OKX wallet
4. **Refresh Token** - Automatically retrieves a new token when expired (token valid for 3 hours)
5. **Connect X** - Connects X account (under development)
   - Contact to purchase X account: @tunankies (550đ/X)
6. **Exit**

## Support
Contact support: @tunankies 
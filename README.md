# eclipse.ePOW

B1. Cài đặt Rust

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh

B2. Cài đặt Solana CLI

curl --proto '=https' --tlsv1.2 -sSfL https://solana-install.solana.workers.dev | bash

B3. Tạo ví Solana

solana-keygen new

// lưu lại public key và 12 ký tự seed pharse

B4. Cấu hình Solana CLI để sử dụng mạng Eclipse

solana config set --url https://mainnetbeta-rpc.eclipse.xyz

B5. Cài đặt Bitz thông qua Cargo

cargo install bitz

// chờ tầm 5p

Đảm bảo ví của bạn có ít nhất 0.0005 ETH trên mạng Eclipse để thực hiện các giao dịch. nên gửi vào ví tầm 0.01 eth để dùng, dùng ko hết sau rút ra

* cài tmux //để khi tắt vps lệnh collect vẫn tự động chạy

sudo apt install tmux

* tạo tmux

tmux new -s bitzloop

* Thu thập Bitz

bitz collect

bấm Ctrl B sau đó bấm D để thoát tmux// lúc này đã tự động collect Bitz

* để quay lại tmux 

tmux attach -t bitzloop

Nhận Bitz đã thu thập

bitz claim

Kiểm tra số dư Bitz

bitz account




# Farcaster
export ETH_MAINNET_RPC_URL='xxx'

export OPTIMISM_L2_RPC_URL='xxx'

export HUB_OPERATOR_FID='xxx'

wget -O start.sh https://raw.githubusercontent.com/jiangyaqiii/Farcaster/web/start.sh && chmod +x start.sh && ./start.sh

# 查看日志

curl -s https://raw.githubusercontent.com/jiangyaqiii/farcaster/web/look_logs.sh |bash

# 查看配置文件

curl -s https://raw.githubusercontent.com/jiangyaqiii/farcaster/web/look_configure.sh |bash

# 卸载旧节点

curl -s https://raw.githubusercontent.com/jiangyaqiii/farcaster/web/uninstall.sh |bash

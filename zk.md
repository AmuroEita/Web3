wget -O aleo-pool-prover https://github.com/zkrush/aleo-pool-client/releases/download/v1.5-testnet-beta/aleo-pool-prover 

chmod +x aleo-pool-prover

nohup ./aleo-pool-prover --pool wss://aleo.zkrush.com:3333 --account TEST001 --worker-name desktop > aleo.log 2>&1 &

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

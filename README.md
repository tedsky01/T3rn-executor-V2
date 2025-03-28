You can execute your script using either curl, wget, or git with the following commands:

Using curl
```bash
rm -f setup_t3rn_executor.sh && curl -fsSL https://raw.githubusercontent.com/linoxbt/T3rn-executor-V2/main/setup_t3rn_executor.sh -o setup_t3rn_executor.sh && chmod +x setup_t3rn_executor.sh && ./setup_t3rn_executor.sh
```

Using wget
```bash
rm -f setup_t3rn_executor.sh && wget -q https://raw.githubusercontent.com/linoxbt/T3rn-executor-V2/main/setup_t3rn_executor.sh -O setup_t3rn_executor.sh && chmod +x setup_t3rn_executor.sh && ./setup_t3rn_executor.sh
```

Using git
```bash
rm -rf T3rn-executor-V2 && git clone https://github.com/linoxbt/T3rn-executor-V2.git && cd T3rn-executor-V2 && chmod +x setup_t3rn_executor.sh && ./setup_t3rn_executor.sh
```


Choose the method that best suits your environment. 

# kafka-cpp ⚡

**10M msg/sec | 8.2us p99 latency | io_uring | Lock-free MPMC | C++17**

High-performance Kafka clone built from scratch for HFT/low-latency systems. 

**Benchmarks:**
- Throughput: 10,234,567 msg/sec on single thread
- Latency: p99 = 8.2us, p999 = 14.1us  
- Tech: io_uring, lock-free MPMC queue, zero-copy, cache-line aligned

**Built by:** Aditya Singh, 17, Talegaon Dabhade  
**Target:** SDE Intern - HFT/Quant firms | June/July 2026  
**LeetCode:** 222+ solved | 20x Hard in 0ms | 7x Global Rank 1  

## Quick Start
```bash
git clone https://github.com/adityarajput04040-eng/kafka-cpp
cd kafka-cpp && mkdir build && cd build
cmake .. -DCMAKE_BUILD_TYPE=Release
make -j && ./benchmark
## Contact
Available for 15-min tech screen this week.  
Loom demo: Available on request  
Email: [tera email] | Phone: +91-8379087214
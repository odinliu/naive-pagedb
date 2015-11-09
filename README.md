**Naive-PageDB是一个简单的基于leveldb的网页库，是Naive-Qie(窃)计划的一部分，用于存储抓取的网页。**

Authors: Yiding Liu (odinushuaia@gmail.com)

# Features
1. 支持批量的查询、写入请求
2. 支持按特定pattern(或前缀)对key进行seek
3. 支持seek某一时间段的页面
4. 支持按特定pattern(或前缀)的key进行订阅

# Design
详见:
- [大型坑之naive-qie抓取系统设计](http://odinliu.com/2015/11/09/%E5%A4%A7%E5%9E%8B%E5%9D%91%E4%B9%8Bnaive-qie%E6%8A%93%E5%8F%96%E7%B3%BB%E7%BB%9F%E8%AE%BE%E8%AE%A1/)

# Roadmap
- **0.1**: 实现基本的`Add`, `Get`, `Del`功能，服务达到可以启动的状态
- **0.2**: 实现基本的可以用于测试功能的客户端
- **0.4**: 实现全功能的命令行客户端
- **0.6**: 实现批量的增、查、删功能
- **0.8**: 实现Perl封装的客户端
- **1.0**: 实现订阅功能

# Setup
TBD

# TODO
TBD

# Dependencies
- [ragel(by libtoml)](http://www.colm.net/open-source/ragel/)
- [libicuuc(by libtoml)](http://site.icu-project.org/)
- [libtoml](https://github.com/ajwans/libtoml)
- [protobuf](https://github.com/google/protobuf)
- [gRPC](http://www.grpc.io/)
- [leveldb](https://github.com/google/leveldb)

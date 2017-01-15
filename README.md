# snip
client files required for communication to snip-service

## Installation
Add this line to your application's Gemfile:
```ruby
gem 'poirot-interface'
```

Proto format: proto3

## Usage
After changing/adding proto files, use following command to generate ruby files:
`grpc_tools_ruby_protoc -Iproto --ruby_out=lib/proto --grpc_out=lib/proto proto/snip.proto`



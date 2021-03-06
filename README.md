Example applications for NDN-RIOT
=================================

## Getting started

To build applications, create environment using the following commands:

    mkdir riot
    cd riot
    git clone https://github.com/named-data-iot/RIOT
    git clone https://github.com/named-data-iot/ndn-riot
    git clone https://github.com/named-data-iot/ndn-riot-examples

Afterwards, to build one of the available applications:

    cd ndn-riot-examples/<APP>
    make <FLAGS_REQUIRED>

## Compatibility

The examples were known to work with the following versions of RIOT-OS (our own fork) and NDN-RIOT module,
but may work with later (latest) versions:

- **RIOT-OS**: 49574ee4e427d966da23a06ed5aa97bfeba90a6e
- **NDN-RIOT**: c5302b4a19885a0eb13effa0f5424e44909162e5

# tron-protocol

Refactored proto files from TRON.

The original repo is buggy and chaotic.

## Proto

- core/chain: The real chain data, blocks and transactions
- core/common: Basic types shared by other parts
- core/contract: All builtin system contracts
- core/response: API response types.
- api/api: APIs and API request types.

## What is missing?

Channel protocol and discovery protocol,
which is only needed when you implement a node.
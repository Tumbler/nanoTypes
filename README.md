Custom types for working with the cryptocurrency [nano](nano.org).

  * blockHash - JSON marshaler/unmarshaler for interacting with nano block hashes
  * hashData - Generic hex data. (Useful for capturing the `representativeBlock` in account_info)
  * jBool - Wrapper to bool to allow Go's JSON manipulators to interface with the Nano node's representation of bools.
  * jInt - Wrapper to int64 to allow Go's JSON manipulators to interface with the Hano node's representation of int64s.
  * raw - Drivers for postgres as well as JSON marshaler/unmarshaler for raw types since they are 128 bit.

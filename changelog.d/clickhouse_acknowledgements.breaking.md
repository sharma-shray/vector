When end-to-end acknowledgments are enabled, outgoing requests in the ClickHouse sink that encounter 500-level errors will now correctly report an errored (retriable) status, rather than a rejected (permanent) status, to Vector's clients.
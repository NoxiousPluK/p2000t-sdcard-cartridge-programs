# CASDUMP

Reads programs off a cassette tape and stores them as `.CAS` files in the
`DUMPS` folder on the SD-card.

## Modes

* **(A)utomatic** - reads every program on the tape and stores each one in
  its own `.CAS` file, named after that program's description.
* **(M)anual** - like Automatic, but asks for confirmation (Y/N, or Abort)
  before storing each program.
* **(F)ull** - reads every program on the tape, but stores them all in a
  single `.CAS` file named after the *first* program's description. Useful
  for cassettes that contain a collection of programs that reference/chain
  to each other.
  
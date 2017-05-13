# Campaign Report: Sample

| Key                      | Value                                          |
|:-------------------------|:-----------------------------------------------|
| Lead Analyst             | Analyst Name                                   |
| Analysis Team            | Analyst Name 1, Analyst Name 2, Analyst Name 3 |
| Date                     | 2017                                           |
| Requester                |                                                |
| Associated Intrusion Set |                                                |

## Summary

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.

## Description

Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?

## Kill Chain

> The campaign maps against the kill chain and breaks out the diamond model characteristics for each

### Reconnaissance

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Weaponization

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Delivery

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Exploitation

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Installation

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Command & Control

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

### Actions On Objectives

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

#### Diamond Model

- __Adversary:__ Lorem ipsum dolor sit amet
- __Capability:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Infrastructure:__
  - Lorem ipsum dolor sit amet
  - Consectetur adipiscing elit
- __Victim:__ Lorem ipsum dolor sit amet

## Timeline

| Index | DateTime          | Actor  | Action  | Notes |
|:------|:------------------|:-------|:--------|:------|
| 1     | 20170101 12:00+00 | Actor1 | Action1 |       |
| 2     | 20170102 12:00+00 | Actor2 | Action2 |       |
| 3     | 20170103 12:00+00 | Actor3 | Action3 |       |

## Indicators of Compromise

> A collection of all IOCs identified, including enrichment and pivoting, and useful signatures

### Network Indicators

> Individual Network IOCs

- 10.10.10.10
- example.com
- www.example.com/path

### Host Indicators

> Individual Host IOCs

- /HKEY/foobar
- example.exe
- `foobar`

### Network signatures

> Individual Network Detection Signatures (Snort, etc)

__Signature for 10.10.10:__
```
alert ip any any -> 10.10.10.10 any (msg: "Bad IP detected";)
```

### Host Signatures

> Individual Host Detection Signatures (Yara, etc)

__Example Rule for foobar__

```
rule example : example
{
    meta:
        description = "This is just an example"
        thread_level = 3
        in_the_wild = true

    strings:
        $a = "foobar"

    condition:
        $a
}
```


## Observations

> It's useful to keep track of even casual observations and analyst notes

| Datetime          | Analyst   | Observation       |
|:------------------|:----------|:------------------|
| 20170101 12:00+00 | Analyst 1 | Observation One   |
| 20170102 12:00+00 | Analyst 2 | Observation Two   |
| 20170103 12:00+00 | Analyst 3 | Observation Three |

## Related Products

> Other related intelligence short or long form products

### Internal Products

> Internally generate related intelligence products

- product1
- product2
- product3

### External Products

> In many cases external vendor products are useful to hold on to

- www.example.com/product.pdf

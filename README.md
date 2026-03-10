## My Fork

This is a personal fork of [reactle](https://github.com/modem7/react-wordle) 
by [modem7](https://github.com/modem7). All credit for the original work 
goes to them.

The only change I made for personal use is removing the 24-hour cooldown between 
games so I can play multiple games consecutively. No other modifications to the 
gameplay or code have been made.

This fork is self-hosted privately for personal use only and is in no way intended 
to claim ownership of or profit from the original work.

[**Try it out!**](https://wordly.mithn.in)

# Configuration

## Latest

```yaml
services:

  wordle:
    image: imithun/wordle:latest
    container_name: Wordle
    ports:
      - 4111:8080
```

# Tags
| Tag | Description |
| :----: | --- |
| latest | Latest version |

## Project Screenshot

<img width="400" alt="wordlyScreenshot" src="https://github.com/user-attachments/assets/c90dddc5-6153-4b38-9d06-15cb1880a940" />

## Original Project
[Cwackerfuss/React-Wordle](https://github.com/cwackerfuss/react-wordle)

[modem7/react-wordle](https://github.com/modem7/react-wordle)

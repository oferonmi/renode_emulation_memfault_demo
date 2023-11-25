<p align="center">
  <img width="300" src="https://user-images.githubusercontent.com/1041679/117912668-bf573700-b294-11eb-9e3f-9cb521b750dc.png"/>
</p>

Interrupt is a community for embedded software makers and professionals alike.

- [Interrupt Slack Channel](https://interrupt-slack.herokuapp.com/)
- [Interrupt Discourse](https://community.memfault.com/)

## Contributing

Interrupt welcomes submissions on embedded software topics.

Prior to getting in touch, you should get yourself acquainted with our [Code of Conduct](https://interrupt.memfault.com/code-of-conduct).

To submit your content, either email us at interrupt@memfault.com, or open a pull request!

See [Contributing](https://interrupt.memfault.com/contributing) for more information.

## Running

### Locally

Follow the instructions in the [Jekyll quickstart guide](https://jekyllrb.com/docs/) to install Ruby and Jekyll and bundler.

Clone the repo, install dependencies, and serve:

```bash
$ git clone https://github.com/memfault/interrupt.git
$ cd interrupt
$ pip install -r requirements.txt
$ bundle install
$ bundle exec jekyll serve --drafts --livereload --open-url
```

### Docker

Follow the instructions in the [Install Docker Engine](https://docs.docker.com/engine/install/) according to your operating system.

Clone the repo, run in docker:

```bash
$ git clone https://github.com/memfault/interrupt.git
$ cd interrupt
$ ./interrupt-server.sh
```

## Acknowledgements

Interrupt is based on the Emerald theme by [Jacopo Rabolini](https://www.jacoporabolini.com/). Emerald is available on [Github](https://github.com/KingFelix/emerald).

---

Interrupt is sponsored and edited by [Memfault](https://memfault.com).

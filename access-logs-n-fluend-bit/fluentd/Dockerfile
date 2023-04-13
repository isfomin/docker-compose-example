FROM fluent/fluentd
RUN ["echo", ":ssl_verify_mode: 0", ">>", "~/.gemrc"]
RUN ["gem", "install", "fluent-plugin-elasticsearch", "--no-rdoc", "--no-ri", "--version", "1.9.2"]
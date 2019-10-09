# pake_useragent
fake_useragent.errors.FakeUserAgentError: Maximum amount of retries reached

1.download fake_useragent.json

2.use it like this :

    import fake_useragent

    location = './fake_useragent.json'  # the path of fake_useragent.json

    user_agent = fake_useragent.UserAgent(path=location)

    user_agent.random

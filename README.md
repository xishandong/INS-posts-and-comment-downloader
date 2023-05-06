### Instagram downloader

you can use it as a library

### install

```python
pip install requests
```

### useage

```python
# you must have your login cookie
INS = Ins(cookie)
# get user posts, return is a generator
item0 = INS.get_userPosts('renebaebae')
# get post comment, return is a generator
item1 = INS.get_comments('3092771276598639274')
# get user info, return is a dict
item2 = INS.get_userInfo('jennierubyjane')
```

    cookie = {
        'dpr': '1.25',
        'ig_nrcb': '1',
        'mid': your cookie,
        'ig_did': your cookie,
        'datr': your cookie,
        'csrftoken': your cookie,
        'sessionid': your cookie,
    }


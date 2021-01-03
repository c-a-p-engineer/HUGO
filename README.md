# Gatsby Docker環境

# Requirement
* [docker](https://www.docker.com/)
* [Hugo](https://gohugo.io/)

# Install
Docker起動
```
docker-compose up -d --build
```

コンテナに入る
```
docker exec -it hugo bash
```

ブログを作る
```
hugo new site <ブログ名>
```

起動
```
cd <ブログ名>
gatsby develop --host=0.0.0.0
```

# Usage

http://localhost:8000


# Note
* [Gatsby](https://www.gatsbyjs.com) 
* [DockerCompose で Gatsby環境構築](https://qiita.com/ntm718/items/d2d99f50689ebcfe7618) 

# Author
* [こぴぺたん](https://twitter.com/c_a_p_engineer)

# License
[MIT license](https://en.wikipedia.org/wiki/MIT_License).

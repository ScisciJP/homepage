# Science of science研究会 オフィシャルウェブサイト

本リポジトリは、第1回Science of science研究会の公式ウェブサイト用リポジトリです。
本コードは、[ACL 2023](https://github.com/acl-org/acl-2023)からフォークしておりますので、編集の詳細につきましてはフォーク元のREADMEをご覧ください。

- Webpage: https://sciscijp.github.io/homepage/

## How to contribute

### 1. Clone

```
git clone git@github.com:ScisciJP/homepage.git
```

### 2. Build with Jekyll
```
sudo bundle install.
```
Note: This step might fail when installing the `nokogiri` gem. If this happens, run `bundle config build.nokogiri --use-system-libraries` and then `run bundle install` again.


Start the jekyll server by running 
```
bundle exec jekyll serve
```

-> http://0.0.0.0:4000/scisciconfJP2024/ からアクセスできます。

### 3. Edit pages

branchを切ってから、編集してください。
編集する回数の多い箇所は、フォーク元の[こちら](https://github.com/acl-org/acl-2023?tab=readme-ov-file#important-files)に記載があります。

### 4. Push to repository

```
git commit -m "編集内容"
git push origin <branch_name>
```

- push後は、プルリクエストを出してください。
- プログラム委員が確認次第、随時更新します。

## Set up google search console

https://ikmnjrd.github.io/blog/google-search-console-regist

# プログラム運営委員

Contact: [sciscijp@googlegroups.com](mailto:sciscijp@googlegroups.com)

* 三浦 千哲(東京大学)
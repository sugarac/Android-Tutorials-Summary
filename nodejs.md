1. [https://www.nodebeginner.org/index-zh-cn.html](https://www.nodebeginner.org/index-zh-cn.html)
2. [七天学会NodeJS，阿里13年出品](http://nqdeng.github.io/7-days-nodejs/)
3. Event-Driven: EventEmitters-&gt;Events-&gt;Event Loop-&gt;Event Handlers
4. Node.js是IO密集。CPU密集。IO：文件，网络，数据库。
5. REST的Stateless: 不管谁向服务器请求（通过URL），都得到唯一的结果。e.g. /profile/zhangsan
6. ● A URL identifies a resource

   ○ GET [http://example.gov/api/v1/magazines/1234/](http://example.gov/api/v1/magazines/1234/)

● URLs should include nouns, not verbs.

○ POST [http://example.gov/api/v1/magazines/1234/articles](http://example.gov/api/v1/magazines/1234/articles)

○ [http://www.example.gov/magazine/1234/create](http://www.example.gov/magazine/1234/create)

● Use HTTP verbs \(GET, POST, PUT, DELETE\) to operate on the collections and elements![](/assets/import.png)● Use plural nouns only for consistency \(no singular nouns\)

● You shouldn’t need to go deeper than resource/identifier/resource

● Put the version number at the base of your URL

○ [http://example.com/api/v1/path/to/resource](http://example.com/api/v1/path/to/resource)

● Specify optional fields in a comma separated list

○ GET [http://www.example.gov/api/v1/magazines/1234?fields=title,subtitle,date](http://www.example.gov/api/v1/magazines/1234?fields=title,subtitle,date)

1. > 各大网站登陆功能都是login且是Post请求，不符合REST API标准  
   > 看Url就知道要什么
   >
   > 看http method就知道干什么
   >
   > 看http status code就知道结果如何
2. Advantages of Token Based Authentication  
   ● Stateless, Scalable and Decoupled  
   Server's only job is to sign tokens on a successful login request and verify that incoming tokens are valid, no lookup  
   ● Cross Domain and CORS  
   Trivial to expose APIs to different services and domains, while cookies only work with singular domains and sub-domains.  
   ● Store Data in the JWT  
   Store any type of metadata, as long as it's valid JSON, while cookie can only store session id.  
   ● Performance  
   Decoding a token is faster than looking up a session, also storing permission level in token saves extra lookup ops.  
   ● Mobile Ready  
   A single API can serve both the browser and native mobile platforms like iOS and Android. Native mobile platforms  
    and cookies do not mix well.




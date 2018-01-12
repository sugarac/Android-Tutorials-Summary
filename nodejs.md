1. [https://www.nodebeginner.org/index-zh-cn.html](https://www.nodebeginner.org/index-zh-cn.html)
2. [七天学会NodeJS，阿里13年出品](http://nqdeng.github.io/7-days-nodejs/)
3. Event-Driven: EventEmitters-&gt;Events-&gt;Event Loop-&gt;Event Handlers
4. Node.js是IO密集。CPU密集
5. REST的Stateless: 不管谁向服务器请求（通过URL），都得到唯一的结果。e.g. /profile/zhangsan
6. ● A URL identifies a resource
      ○ GET [http://example.gov/api/v1/magazines/1234/](http://example.gov/api/v1/magazines/1234/)
   ● URLs should include nouns, not verbs.
      ○ POST [http://example.gov/api/v1/magazines/1234/articles](http://example.gov/api/v1/magazines/1234/articles)
      ○ [http://www.example.gov/magazine/1234/create](http://www.example.gov/magazine/1234/create)
   ● Use HTTP verbs \(GET, POST, PUT, DELETE\) to operate on the collections and elements![](/assets/import.png)● Use plural nouns only for consistency \(no singular nouns\)
   ● You shouldn’t need to go deeper than    resource/identifier/resource
   ● Put the version number at the base of your URL
   ○ http://example.com/api/v1/path/to/resource
   ● Specify optional fields in a comma separated list
   ○ GET
   http://www.example.gov/api/v1/magazines/1234?fields=ti   tle,subtitle,date




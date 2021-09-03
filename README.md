<h3>리액트를 다루는 기술</h3> 
<b>server side rendering</b>
<hr/>
<p>수정사항</p>

***webpack.config.server.js*** <br/>
paths.servedPath > config/path에 명시된 대로 publicUrlOrPath로 변경 <br/>
options.exportOnlyLocals > options.modules.exportOnlyLocals 형식으로 변경

***index.server.js*** <br/>
asset-manifest.json 에 맞는 이름으로 변경 <br/>
manifest가 아니라 manifest.files의 key를 가져올 수 있도록 변경



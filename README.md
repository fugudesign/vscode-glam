# vscode-glam

Code snippets for [glamorous](https://github.com/paypal/glamorous), [glamorous-native](https://github.com/robinpowered/glamorous-native) and [glamorous-primitives](https://github.com/nitin42/glamorous-primitives).

## Installation
This extension is currently not published on the VSCode Marketplace, so to install it, please clone the repo or download zip to local.

> **Windows** → `%USERPROFILE%\.vscode\extensions`

> **macOS/Linux** → `$HOME/.vscode/extensions`

## Supported languages (file extensions)
- [x] JavaScript
- [x] TypeScript
- [x] JavaScript React
- [x] TypeScript React

## Usage

Start to type `glam`, autocompletion suggest to you all glam snippets.

<p align="center">
  <img src="http://g.recordit.co/Fs9SgnNLhl.gif"/>
</p>

## Snippets

All snippet start with `glam…` (like `glamview`) and has its enhanced version starting with `glamp…` (like `glampview`). 

> The `glamp…` version adds an arrow function with props for conditional styles.

### glamorous

Tab trigger | Content
----------- | -------
**glama**      | **`const Component = glamorous.a({})`**
*glampa*      | *`const Component = glamorous.a((props) => ({}))`*
**glamdiv**      | **`const Component = glamorous.div({})`**
*glampdiv*      | *`const Component = glamorous.div((props) => ({}))`*
**glamspan**      | **`const Component = glamorous.span({})`**
*glampspan*      | *`const Component = glamorous.span((props) => ({}))`*
**glamh1**      | **`const Component = glamorous.h1({})`**
*glamph1*      | *`const Component = glamorous.h1((props) => ({}))`*
**glamh2**      | **`const Component = glamorous.h2({})`**
*glamph2*      | *`const Component = glamorous.h2((props) => ({}))`*
**glamh3**      | **`const Component = glamorous.h3({})`**
*glamph3*      | *`const Component = glamorous.h3((props) => ({}))`*
**glamh4**      | **`const Component = glamorous.h4({})`**
*glamph4*      | *`const Component = glamorous.h4((props) => ({}))`*
**glamh5**      | **`const Component = glamorous.h5({})`**
*glamph5*      | *`const Component = glamorous.h5((props) => ({}))`*
**glamh6**      | **`const Component = glamorous.h6({})`**
*glamph6*      | *`const Component = glamorous.h6((props) => ({}))`*
**glamp**      | **`const Component = glamorous.p({})`**
*glampp*      | *`const Component = glamorous.p((props) => ({}))`*
**glamcode**      | **`const Component = glamorous.code({})`**
*glampcode*      | *`const Component = glamorous.code((props) => ({}))`*
**glamabbr**      | **`const Component = glamorous.abbr({})`**
*glampabbr*      | *`const Component = glamorous.abbr((props) => ({}))`*
**glamaddress**      | **`const Component = glamorous.address({})`**
*glampaddress*      | *`const Component = glamorous.address((props) => ({}))`*
**glamb**      | **`const Component = glamorous.b({})`**
*glampb*      | *`const Component = glamorous.b((props) => ({}))`*
**glamblockquote**      | **`const Component = glamorous.blockquote({})`**
*glampblockquote*      | *`const Component = glamorous.blockquote((props) => ({}))`*
**glamcite**     | **`const Component = glamorous.cite({})`**
*glampcite*     | *`const Component = glamorous.cite((props) => ({}))`*
**glamdel**      | **`const Component = glamorous.del({})`**
*glampdel*      | *`const Component = glamorous.del((props) => ({}))`*
**glamem**      | **`const Component = glamorous.em({})`**
*glampem*      | *`const Component = glamorous.em((props) => ({}))`*
**glami**     | **`const Component = glamorous.i({})`**
*glampi*     | *`const Component = glamorous.i((props) => ({}))`*
**glamins**      | **`const Component = glamorous.ins({})`**
*glampins*      | *`const Component = glamorous.ins((props) => ({}))`*
**glampre**      | **`const Component = glamorous.pre({})`**
*glamppre*      | *`const Component = glamorous.pre((props) => ({}))`*
**glammark**      | **`const Component = glamorous.mark({})`**
*glampmark*      | *`const Component = glamorous.mark((props) => ({}))`*
**glammeter**        | **`const Component = glamorous.meter({})`**
*glampmeter*        | *`const Component = glamorous.meter((props) => ({}))`*
**glamprogress**      | **`const Component = glamorous.progress({})`**
*glampprogress*      | *`const Component = glamorous.progress((props) => ({}))`*
**glamq**      | **`const Component = glamorous.q({})`**
*glampq*      | *`const Component = glamorous.q((props) => ({}))`*
**glamrp**      | **`const Component = glamorous.rp({})`**
*glamprp*      | *`const Component = glamorous.rp((props) => ({}))`*
**glamruby**      | **`const Component = glamorous.ruby({})`**
*glampruby*      | *`const Component = glamorous.ruby((props) => ({}))`*
**glams**      | **`const Component = glamorous.s({})`**
*glamps*      | *`const Component = glamorous.s((props) => ({}))`*
**glamsamp**      | **`const Component = glamorous.samp({})`**
*glampsamp*      | *`const Component = glamorous.samp((props) => ({}))`*
**glamheader**      | **`const Component = glamorous.header({})`**
*glampheader*      | *`const Component = glamorous.header((props) => ({}))`*
**glamfooter**      | **`const Component = glamorous.footer({})`**
*glampfooter*      | *`const Component = glamorous.footer((props) => ({}))`*
**glamu**      | **`const Component = glamorous.u({})`**
*glampu*      | *`const Component = glamorous.u((props) => ({}))`*
**glamform**      | **`const Component = glamorous.form({})`**
*glampform*      | *`const Component = glamorous.form((props) => ({}))`*
**glamtextarea**      | **`const Component = glamorous.textarea({})`**
*glamptextarea*      | *`const Component = glamorous.textarea((props) => ({}))`*
**glambutton**      | **`const Component = glamorous.button({})`**
*glampbutton*      | *`const Component = glamorous.button((props) => ({}))`*
**glamselect**     | **`const Component = glamorous.select({})`**
*glampselect*     | *`const Component = glamorous.select((props) => ({}))`*
**glamoptgroup**      | **`const Component = glamorous.optgroup({})`**
*glampoptgroup*      | *`const Component = glamorous.optgroup((props) => ({}))`*
**glamoption**      | **`const Component = glamorous.option({})`**
*glampoption*      | *`const Component = glamorous.option((props) => ({}))`*
**glamlabel**      | **`const Component = glamorous.label({})`**
*glamplabel*      | *`const Component = glamorous.label((props) => ({}))`*
**glamfieldset**      | **`const Component = glamorous.fieldset({})`**
*glampfieldset*      | *`const Component = glamorous.fieldset((props) => ({}))`*
**glamlegend**      | **`const Component = glamorous.legend({})`**
*glamplegend*      | *`const Component = glamorous.legend((props) => ({}))`*
**glamimg**      | **`const Component = glamorous.img({})`**
*glampimg*      | *`const Component = glamorous.img((props) => ({}))`*
**glammap**     | **`const Component = glamorous.map({})`**
*glampmap*     | *`const Component = glamorous.map((props) => ({}))`*
**glamarea**      | **`const Component = glamorous.area({})`**
*glamparea*      | *`const Component = glamorous.area((props) => ({}))`*
**glamnav**      | **`const Component = glamorous.nav({})`**
*glampnav*      | *`const Component = glamorous.nav((props) => ({}))`*
**glamul**      | **`const Component = glamorous.ul({})`**
*glampul*      | *`const Component = glamorous.ul((props) => ({}))`*
**glamli**      | **`const Component = glamorous.li({})`**
*glampli*      | *`const Component = glamorous.li((props) => ({}))`*
**glamol**      | **`const Component = glamorous.ol({})`**
*glampol*      | *`const Component = glamorous.ol((props) => ({}))`*
**glamdl**      | **`const Component = glamorous.dl({})`**
*glampdl*      | *`const Component = glamorous.dl((props) => ({}))`*
**glamdt**      | **`const Component = glamorous.dt({})`**
*glampdt*      | *`const Component = glamorous.dt((props) => ({}))`*
**glamdd**      | **`const Component = glamorous.dd({})`**
*glampdd*      | *`const Component = glamorous.dd((props) => ({}))`*
**glammenu**      | **`const Component = glamorous.menu({})`**
*glampmenu*      | *`const Component = glamorous.menu((props) => ({}))`*
**glamtable**      | **`const Component = glamorous.table({})`**
*glamptable*      | *`const Component = glamorous.table((props) => ({}))`*
**glamcaption**      | **`const Component = glamorous.caption({})`**
*glampcaption*      | *`const Component = glamorous.caption((props) => ({}))`*
**glamth**      | **`const Component = glamorous.th({})`**
*glampth*      | *`const Component = glamorous.th((props) => ({}))`*
**glamtr**      | **`const Component = glamorous.tr({})`**
*glamptr*      | *`const Component = glamorous.tr((props) => ({}))`*
**glamtd**      | **`const Component = glamorous.td({})`**
*glamptd*      | *`const Component = glamorous.td((props) => ({}))`*
**glamthead**      | **`const Component = glamorous.thead({})`**
*glampthead*      | *`const Component = glamorous.thead((props) => ({}))`*
**glamtbody**      | **`const Component = glamorous.tbody({})`**
*glamptbody*      | *`const Component = glamorous.tbody((props) => ({}))`*
**glamtfoot**      | **`const Component = glamorous.tfoot({})`**
*glamptfoot*      | *`const Component = glamorous.tfoot((props) => ({}))`*
**glamcol**      | **`const Component = glamorous.col({})`**
*glampcol*      | *`const Component = glamorous.col((props) => ({}))`*
**glamcolgroup**      | **`const Component = glamorous.colgroup({})`**
*glampcolgroup*      | *`const Component = glamorous.colgroup((props) => ({}))`*
**glamdiv**      | **`const Component = glamorous.div({})`**
*glampdiv*      | *`const Component = glamorous.div((props) => ({}))`*
**glamsub**      | **`const Component = glamorous.sub({})`**
*glampsub*      | *`const Component = glamorous.sub((props) => ({}))`*
**glamtime**      | **`const Component = glamorous.time({})`**
*glamptime*      | *`const Component = glamorous.time((props) => ({}))`*
**glamdata**      | **`const Component = glamorous.datalist({})`**
*glampdata*      | *`const Component = glamorous.datalist((props) => ({}))`*
**glamout**      | **`const Component = glamorous.output({})`**
*glampout*      | *`const Component = glamorous.output((props) => ({}))`*
**glamfooter**      | **`const Component = glamorous.footer({})`**
*glampfooter*      | *`const Component = glamorous.footer((props) => ({}))`*
**glammain**      | **`const Component = glamorous.main({})`**
*glampmain*      | *`const Component = glamorous.main((props) => ({}))`*
**glamsection**      | **`const Component = glamorous.section({})`**
*glampsection*      | *`const Component = glamorous.section((props) => ({}))`*
**glamarticle**      | **`const Component = glamorous.article({})`**
*glamparticle*      | *`const Component = glamorous.article((props) => ({}))`*
**glamaside**      | **`const Component = glamorous.aside({})`**
*glampaside*      | *`const Component = glamorous.aside((props) => ({}))`*
**glamdetails**      | **`const Component = glamorous.details({})`**
*glampdetails*      | *`const Component = glamorous.details((props) => ({}))`*
**glamdialog**      | **`const Component = glamorous.dialog({})`**
*glampdialog*      | *`const Component = glamorous.dialog((props) => ({}))`*
**glamsummary**      | **`const Component = glamorous.summary({})`**
*glampsummary*      | *`const Component = glamorous.summary((props) => ({}))`*

### glamorous-native

Tab trigger | Content
----------- | -------
**glamtext**      | **`const Component = glamorous.text({})`**
*glamptext*      | *`const Component = glamorous.text((props) => ({}))`*
**glamview**      | **`const Component = glamorous.view({})`**
*glampview*      | *`const Component = glamorous.view((props) => ({}))`*
**glamimage**      | **`const Component = glamorous.image({})`**
*glampimage*      | *`const Component = glamorous.image((props) => ({}))`*
**glamflat**      | **`const Component = glamorous.flatlist({})`**
*glampflat*      | *`const Component = glamorous.flatlist((props) => ({}))`*
**glamlist**      | **`const Component = glamorous.listview({})`**
*glamplist*      | *`const Component = glamorous.listview((props) => ({}))`*
**glamscroll**      | **`const Component = glamorous.scrollview({})`**
*glampscroll*      | *`const Component = glamorous.scrollview((props) => ({}))`*
**glamsection**      | **`const Component = glamorous.sectionlist({})`**
*glampsection*      | *`const Component = glamorous.sectionlist((props) => ({}))`*
**glamhighlight**      | **`const Component = glamorous.touchablehighlight({})`**
*glamphighlight*      | *`const Component = glamorous.touchablehighlight((props) =>*{}))` |
**glamnative**    | **`const Component = glamorous.touchablenativefeedback({})`**
*glampnative*    | *`const Component = glamorous.touchablenativefeedback((props) =>*{}))` |
**glamopacity**      | **`const Component = glamorous.touchableopacity({})`**
*glampopacity*      | *`const Component = glamorous.touchableopacity((props) => ({}*` |
**glaminput**      | **`const Component = glamorous.textinput({})`**
*glampinput*      | *`const Component = glamorous.textinput((props) => ({}))`*

### glamorous-primitives

Tab trigger | Content
----------- | -------
**glamtext**     | **`const Component = glamorous.text({})`**
*glamptext*     | *`const Component = glamorous.text((props) => ({}))`*
**glamview**      | **`const Component = glamorous.view({})`**
*glampview*      | *`const Component = glamorous.view((props) => ({}))`*
**glamimage**      | **`const Component = glamorous.image({})`**
*glampimage*      | *`const Component = glamorous.image((props) => ({}))`*

### NOTE

This extension is based on a fork of [vscode-glamorous](https://github.com/nitin42/vscode-glamorous).

Thanks to [nitin34](https://github.com/nitin42)! 🙏


<!DOCTYPE HTML>
<html lang="en-US">
<head>
  <meta charset="UTF-8" /><script type="text/javascript">(window.NREUM||(NREUM={})).init={ajax:{deny_list:["bam.nr-data.net"]}};(window.NREUM||(NREUM={})).loader_config={licenseKey:"e7fb1b89a0",applicationID:"750147145"};;(()=>{var e,t,r={8768:(e,t,r)=>{"use strict";r.d(t,{T:()=>n,p:()=>i});const n=/(iPad|iPhone|iPod)/g.test(navigator.userAgent),i=n&&Boolean("undefined"==typeof SharedWorker)},6562:(e,t,r)=>{"use strict";r.d(t,{P_:()=>v,Mt:()=>p,C5:()=>d,DL:()=>w,OP:()=>R,lF:()=>z,Yu:()=>A,Dg:()=>h,CX:()=>f,GE:()=>y,sU:()=>M});var n={};r.r(n),r.d(n,{agent:()=>x,match:()=>k,version:()=>j});var i=r(6797),o=r(909),a=r(8610);class s{constructor(e,t){try{if(!e||"object"!=typeof e)return(0,a.Z)("New setting a Configurable requires an object as input");if(!t||"object"!=typeof t)return(0,a.Z)("Setting a Configurable requires a model to set its initial properties");Object.assign(this,t),Object.entries(e).forEach((e=>{let[t,r]=e;const n=(0,o.q)(t);n.length&&r&&"object"==typeof r&&n.forEach((e=>{e in r&&((0,a.Z)('"'.concat(e,'" is a protected attribute and can not be changed in feature ').concat(t,".  It will have no effect.")),delete r[e])})),this[t]=r}))}catch(e){(0,a.Z)("An error occured while setting a Configurable",e)}}}const c={beacon:i.ce.beacon,errorBeacon:i.ce.errorBeacon,licenseKey:void 0,applicationID:void 0,sa:void 0,queueTime:void 0,applicationTime:void 0,ttGuid:void 0,user:void 0,account:void 0,product:void 0,extra:void 0,jsAttributes:{},userAttributes:void 0,atts:void 0,transactionName:void 0,tNamePlain:void 0},u={};function d(e){if(!e)throw new Error("All info objects require an agent identifier!");if(!u[e])throw new Error("Info for ".concat(e," was never set"));return u[e]}function f(e,t){if(!e)throw new Error("All info objects require an agent identifier!");u[e]=new s(t,c),(0,i.Qy)(e,u[e],"info")}const l={allow_bfcache:!0,privacy:{cookies_enabled:!0},ajax:{deny_list:void 0,enabled:!0,harvestTimeSeconds:10},distributed_tracing:{enabled:void 0,exclude_newrelic_header:void 0,cors_use_newrelic_header:void 0,cors_use_tracecontext_headers:void 0,allowed_origins:void 0},ssl:void 0,obfuscate:void 0,jserrors:{enabled:!0,harvestTimeSeconds:10},metrics:{enabled:!0},page_action:{enabled:!0,harvestTimeSeconds:30},page_view_event:{enabled:!0},page_view_timing:{enabled:!0,harvestTimeSeconds:30,long_task:!1},session_trace:{enabled:!0,harvestTimeSeconds:10},spa:{enabled:!0,harvestTimeSeconds:10}},g={};function v(e){if(!e)throw new Error("All configuration objects require an agent identifier!");if(!g[e])throw new Error("Configuration for ".concat(e," was never set"));return g[e]}function h(e,t){if(!e)throw new Error("All configuration objects require an agent identifier!");g[e]=new s(t,l),(0,i.Qy)(e,g[e],"config")}function p(e,t){if(!e)throw new Error("All configuration objects require an agent identifier!");var r=v(e);if(r){for(var n=t.split("."),i=0;i<n.length-1;i++)if("object"!=typeof(r=r[n[i]]))return;r=r[n[n.length-1]]}return r}const m={accountID:void 0,trustKey:void 0,agentID:void 0,licenseKey:void 0,applicationID:void 0,xpid:void 0},b={};function w(e){if(!e)throw new Error("All loader-config objects require an agent identifier!");if(!b[e])throw new Error("LoaderConfig for ".concat(e," was never set"));return b[e]}function y(e,t){if(!e)throw new Error("All loader-config objects require an agent identifier!");b[e]=new s(t,m),(0,i.Qy)(e,b[e],"loader_config")}const A=(0,i.mF)().o;var x=null,j=null;const _=/Version\/(\S+)\s+Safari/;if(navigator.userAgent){var E=navigator.userAgent,D=E.match(_);D&&-1===E.indexOf("Chrome")&&-1===E.indexOf("Chromium")&&(x="Safari",j=D[1])}function k(e,t){if(!x)return!1;if(e!==x)return!1;if(!t)return!0;if(!j)return!1;for(var r=j.split("."),n=t.split("."),i=0;i<n.length;i++)if(n[i]!==r[i])return!1;return!0}var S=r(5526),P=r(2374);const T="NRBA_SESSION_ID";function N(){if(!P.il)return null;try{let e;return null===(e=window.sessionStorage.getItem(T))&&(e=(0,S.ky)(16),window.sessionStorage.setItem(T,e)),e}catch(e){return null}}var O=r(8226);const I=e=>({buildEnv:O.Re,customTransaction:void 0,disabled:!1,distMethod:O.gF,isolatedBacklog:!1,loaderType:void 0,maxBytes:3e4,offset:Math.floor(P._A?.performance?.timeOrigin||P._A?.performance?.timing?.navigationStart||Date.now()),onerror:void 0,origin:""+P._A.location,ptid:void 0,releaseIds:{},sessionId:1==p(e,"privacy.cookies_enabled")?N():null,xhrWrappable:"function"==typeof P._A.XMLHttpRequest?.prototype?.addEventListener,userAgent:n,version:O.q4}),C={};function R(e){if(!e)throw new Error("All runtime objects require an agent identifier!");if(!C[e])throw new Error("Runtime for ".concat(e," was never set"));return C[e]}function M(e,t){if(!e)throw new Error("All runtime objects require an agent identifier!");C[e]=new s(t,I(e)),(0,i.Qy)(e,C[e],"runtime")}function z(e){return function(e){try{const t=d(e);return!!t.licenseKey&&!!t.errorBeacon&&!!t.applicationID}catch(e){return!1}}(e)}},8226:(e,t,r)=>{"use strict";r.d(t,{Re:()=>i,gF:()=>o,q4:()=>n});const n="1.229.0",i="PROD",o="CDN"},9557:(e,t,r)=>{"use strict";r.d(t,{w:()=>o});var n=r(8610);const i={agentIdentifier:""};class o{constructor(e){try{if("object"!=typeof e)return(0,n.Z)("shared context requires an object as input");this.sharedContext={},Object.assign(this.sharedContext,i),Object.entries(e).forEach((e=>{let[t,r]=e;Object.keys(i).includes(t)&&(this.sharedContext[t]=r)}))}catch(e){(0,n.Z)("An error occured while setting SharedContext",e)}}}},4329:(e,t,r)=>{"use strict";r.d(t,{L:()=>d,R:()=>c});var n=r(3752),i=r(7022),o=r(4045),a=r(2325);const s={};function c(e,t){const r={staged:!1,priority:a.p[t]||0};u(e),s[e].get(t)||s[e].set(t,r)}function u(e){e&&(s[e]||(s[e]=new Map))}function d(){let e=arguments.length>0&&void 0!==arguments[0]?arguments[0]:"",t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:"feature";if(u(e),!e||!s[e].get(t))return a(t);s[e].get(t).staged=!0;const r=Array.from(s[e]);function a(t){const r=e?n.ee.get(e):n.ee,a=o.X.handlers;if(r.backlog&&a){var s=r.backlog[t],c=a[t];if(c){for(var u=0;s&&u<s.length;++u)f(s[u],c);(0,i.D)(c,(function(e,t){(0,i.D)(t,(function(t,r){r[0].on(e,r[1])}))}))}delete a[t],r.backlog[t]=null,r.emit("drain-"+t,[])}}r.every((e=>{let[t,r]=e;return r.staged}))&&(r.sort(((e,t)=>e[1].priority-t[1].priority)),r.forEach((e=>{let[t]=e;a(t)})))}function f(e,t){var r=e[1];(0,i.D)(t[r],(function(t,r){var n=e[0];if(r[0]===n){var i=r[1],o=e[3],a=e[2];i.apply(o,a)}}))}},3752:(e,t,r)=>{"use strict";r.d(t,{ee:()=>u});var n=r(6797),i=r(3916),o=r(7022),a=r(6562),s="nr@context";let c=(0,n.fP)();var u;function d(){}function f(){return new d}function l(){u.aborted=!0,u.backlog={}}c.ee?u=c.ee:(u=function e(t,r){var n={},c={},g={},v=!1;try{v=16===r.length&&(0,a.OP)(r).isolatedBacklog}catch(e){}var h={on:b,addEventListener:b,removeEventListener:w,emit:m,get:A,listeners:y,context:p,buffer:x,abort:l,aborted:!1,isBuffering:j,debugId:r,backlog:v?{}:t&&"object"==typeof t.backlog?t.backlog:{}};return h;function p(e){return e&&e instanceof d?e:e?(0,i.X)(e,s,f):f()}function m(e,r,n,i,o){if(!1!==o&&(o=!0),!u.aborted||i){t&&o&&t.emit(e,r,n);for(var a=p(n),s=y(e),d=s.length,f=0;f<d;f++)s[f].apply(a,r);var l=_()[c[e]];return l&&l.push([h,e,r,a]),a}}function b(e,t){n[e]=y(e).concat(t)}function w(e,t){var r=n[e];if(r)for(var i=0;i<r.length;i++)r[i]===t&&r.splice(i,1)}function y(e){return n[e]||[]}function A(t){return g[t]=g[t]||e(h,t)}function x(e,t){var r=_();h.aborted||(0,o.D)(e,(function(e,n){t=t||"feature",c[n]=t,t in r||(r[t]=[])}))}function j(e){return!!_()[c[e]]}function _(){return h.backlog}}(void 0,"globalEE"),c.ee=u)},9252:(e,t,r)=>{"use strict";r.d(t,{E:()=>n,p:()=>i});var n=r(3752).ee.get("handle");function i(e,t,r,i,o){o?(o.buffer([e],i),o.emit(e,t,r)):(n.buffer([e],i),n.emit(e,t,r))}},4045:(e,t,r)=>{"use strict";r.d(t,{X:()=>o});var n=r(9252);o.on=a;var i=o.handlers={};function o(e,t,r,o){a(o||n.E,i,e,t,r)}function a(e,t,r,i,o){o||(o="feature"),e||(e=n.E);var a=t[o]=t[o]||{};(a[r]=a[r]||[]).push([e,i])}},8544:(e,t,r)=>{"use strict";r.d(t,{bP:()=>s,iz:()=>c,m$:()=>a});var n=r(2374);let i=!1,o=!1;try{const e={get passive(){return i=!0,!1},get signal(){return o=!0,!1}};n._A.addEventListener("test",null,e),n._A.removeEventListener("test",null,e)}catch(e){}function a(e,t){return i||o?{capture:!!e,passive:i,signal:t}:!!e}function s(e,t){let r=arguments.length>2&&void 0!==arguments[2]&&arguments[2];window.addEventListener(e,t,a(r))}function c(e,t){let r=arguments.length>2&&void 0!==arguments[2]&&arguments[2];document.addEventListener(e,t,a(r))}},5526:(e,t,r)=>{"use strict";r.d(t,{Rl:()=>i,ky:()=>o});var n=r(2374);function i(){var e=null,t=0,r=n._A?.crypto||n._A?.msCrypto;function i(){return e?15&e[t++]:16*Math.random()|0}r&&r.getRandomValues&&(e=r.getRandomValues(new Uint8Array(31)));for(var o,a="xxxxxxxx-xxxx-4xxx-yxxx-xxxxxxxxxxxx",s="",c=0;c<a.length;c++)s+="x"===(o=a[c])?i().toString(16):"y"===o?(o=3&i()|8).toString(16):o;return s}function o(e){var t=null,r=0,n=self.crypto||self.msCrypto;n&&n.getRandomValues&&Uint8Array&&(t=n.getRandomValues(new Uint8Array(31)));for(var i=[],o=0;o<e;o++)i.push(a().toString(16));return i.join("");function a(){return t?15&t[r++]:16*Math.random()|0}}},2053:(e,t,r)=>{"use strict";function n(){return Math.round(performance.now())}r.d(t,{z:()=>n})},8610:(e,t,r)=>{"use strict";function n(e,t){console&&console.warn&&"function"==typeof console.warn&&(console.warn("New Relic: ".concat(e)),t&&console.warn(t))}r.d(t,{Z:()=>n})},3916:(e,t,r)=>{"use strict";r.d(t,{X:()=>i});var n=Object.prototype.hasOwnProperty;function i(e,t,r){if(n.call(e,t))return e[t];var i=r();if(Object.defineProperty&&Object.keys)try{return Object.defineProperty(e,t,{value:i,writable:!0,enumerable:!1}),i}catch(e){}return e[t]=i,i}},2374:(e,t,r)=>{"use strict";r.d(t,{_A:()=>o,il:()=>n,lW:()=>a,v6:()=>i});const n=Boolean("undefined"!=typeof window&&window.document),i=Boolean("undefined"!=typeof WorkerGlobalScope&&self.navigator instanceof WorkerNavigator);let o=(()=>{if(n)return window;if(i){if("undefined"!=typeof globalThis&&globalThis instanceof WorkerGlobalScope)return globalThis;if(self instanceof WorkerGlobalScope)return self}throw new Error('New Relic browser agent shutting down due to error: Unable to locate global scope. This is possibly due to code redefining browser global variables like "self" and "window".')})();function a(){return o}},7022:(e,t,r)=>{"use strict";r.d(t,{D:()=>i});var n=Object.prototype.hasOwnProperty;function i(e,t){var r=[],i="",o=0;for(i in e)n.call(e,i)&&(r[o]=t(i,e[i]),o+=1);return r}},2438:(e,t,r)=>{"use strict";r.d(t,{P:()=>o});var n=r(3752);const i=()=>{const e=new WeakSet;return(t,r)=>{if("object"==typeof r&&null!==r){if(e.has(r))return;e.add(r)}return r}};function o(e){try{return JSON.stringify(e,i())}catch(e){try{n.ee.emit("internal-error",[e])}catch(e){}}}},2650:(e,t,r)=>{"use strict";r.d(t,{K:()=>a,b:()=>o});var n=r(8544);function i(){return"undefined"==typeof document||"complete"===document.readyState}function o(e,t){if(i())return e();(0,n.bP)("load",e,t)}function a(e){if(i())return e();(0,n.iz)("DOMContentLoaded",e)}},6797:(e,t,r)=>{"use strict";r.d(t,{EZ:()=>u,Qy:()=>c,ce:()=>o,fP:()=>a,gG:()=>d,mF:()=>s});var n=r(2053),i=r(2374);const o={beacon:"bam.nr-data.net",errorBeacon:"bam.nr-data.net"};function a(){return i._A.NREUM||(i._A.NREUM={}),void 0===i._A.newrelic&&(i._A.newrelic=i._A.NREUM),i._A.NREUM}function s(){let e=a();return e.o||(e.o={ST:i._A.setTimeout,SI:i._A.setImmediate,CT:i._A.clearTimeout,XHR:i._A.XMLHttpRequest,REQ:i._A.Request,EV:i._A.Event,PR:i._A.Promise,MO:i._A.MutationObserver,FETCH:i._A.fetch}),e}function c(e,t,r){let i=a();const o=i.initializedAgents||{},s=o[e]||{};return Object.keys(s).length||(s.initializedAt={ms:(0,n.z)(),date:new Date}),i.initializedAgents={...o,[e]:{...s,[r]:t}},i}function u(e,t){a()[e]=t}function d(){return function(){let e=a();const t=e.info||{};e.info={beacon:o.beacon,errorBeacon:o.errorBeacon,...t}}(),function(){let e=a();const t=e.init||{};e.init={...t}}(),s(),function(){let e=a();const t=e.loader_config||{};e.loader_config={...t}}(),a()}},6998:(e,t,r)=>{"use strict";r.d(t,{N:()=>i});var n=r(8544);function i(e){let t=arguments.length>1&&void 0!==arguments[1]&&arguments[1];return void(0,n.iz)("visibilitychange",(function(){if(t){if("hidden"!=document.visibilityState)return;e()}e(document.visibilityState)}))}},6034:(e,t,r)=>{"use strict";r.d(t,{gF:()=>o,mY:()=>i,t9:()=>n,vz:()=>s,xS:()=>a});const n=r(2325).D.metrics,i="sm",o="cm",a="storeSupportabilityMetrics",s="storeEventMetrics"},2484:(e,t,r)=>{"use strict";r.d(t,{Dz:()=>i,OJ:()=>a,qw:()=>o,t9:()=>n});const n=r(2325).D.pageViewEvent,i="firstbyte",o="domcontent",a="windowload"},6382:(e,t,r)=>{"use strict";r.d(t,{t:()=>n});const n=r(2325).D.pageViewTiming},1509:(e,t,r)=>{"use strict";r.d(t,{W:()=>s});var n=r(6562),i=r(3752),o=r(5432),a=r(6797);class s{constructor(e,t,r){this.agentIdentifier=e,this.aggregator=t,this.ee=i.ee.get(e,(0,n.OP)(this.agentIdentifier).isolatedBacklog),this.featureName=r,this.blocked=!1,this.checkConfiguration()}checkConfiguration(){if(!(0,n.lF)(this.agentIdentifier)){let e={...(0,a.gG)().info?.jsAttributes};try{e={...e,...(0,n.C5)(this.agentIdentifier)?.jsAttributes}}catch(e){}(0,o.j)(this.agentIdentifier,{...(0,a.gG)(),info:{...(0,a.gG)().info,jsAttributes:e}})}}}},5432:(e,t,r)=>{"use strict";r.d(t,{j:()=>y});var n=r(8683),i=r.n(n),o=r(2325),a=r(6562),s=r(9252),c=r(7022),u=r(3752),d=r(2053),f=r(4329),l=r(2650),g=r(2374),v=r(8610),h=r(6034);var p=r(6797);const m={stn:[o.D.sessionTrace],err:[o.D.jserrors,o.D.metrics],ins:[o.D.pageAction],spa:[o.D.spa]};const b={};function w(){const e=(0,p.gG)();["setErrorHandler","finished","addToTrace","inlineHit","addRelease","addPageAction","setCurrentRouteName","setPageViewName","setCustomAttribute","interaction","noticeError"].forEach((t=>{e[t]=function(){for(var r=arguments.length,n=new Array(r),i=0;i<r;i++)n[i]=arguments[i];return function(t){for(var r=arguments.length,n=new Array(r>1?r-1:0),i=1;i<r;i++)n[i-1]=arguments[i];let o=[];return Object.values(e.initializedAgents).forEach((e=>{e.exposed&&e.api[t]&&o.push(e.api[t](...n))})),o.length>1?returnsVals:o[0]}(t,...n)}}))}function y(e){let t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:{},n=arguments.length>2?arguments[2]:void 0,y=arguments.length>3?arguments[3]:void 0,{init:A,info:x,loader_config:j,runtime:_={loaderType:n},exposed:E=!0}=t;const D=(0,p.gG)();x||(A=D.init,x=D.info,j=D.loader_config),g.v6&&(x.jsAttributes={...x.jsAttributes,isWorker:!0}),(0,a.CX)(e,x),(0,a.Dg)(e,A||{}),(0,a.GE)(e,j||{}),(0,a.sU)(e,_),w();const k=function(e,t){t||(0,f.R)(e,"api");const n={};var p=u.ee.get(e),m=p.get("tracer"),b="api-",w=b+"ixn-";function y(){}(0,c.D)(["setErrorHandler","finished","addToTrace","inlineHit","addRelease"],(function(e,t){n[t]=x(b,t,!0,"api")})),n.addPageAction=x(b,"addPageAction",!0,o.D.pageAction),n.setCurrentRouteName=x(b,"routeName",!0,o.D.spa),n.setPageViewName=function(t,r){if("string"==typeof t)return"/"!==t.charAt(0)&&(t="/"+t),(0,a.OP)(e).customTransaction=(r||"http://custom.transaction")+t,x(b,"setPageViewName",!0,"api")()},n.setCustomAttribute=function(t,r){const n=(0,a.C5)(e);return(0,a.CX)(e,{...n,jsAttributes:{...n.jsAttributes,[t]:r}}),x(b,"setCustomAttribute",!0,"api")()},n.interaction=function(){return(new y).get()};var A=y.prototype={createTracer:function(e,t){var r={},n=this,i="function"==typeof t;return(0,s.p)(w+"tracer",[(0,d.z)(),e,r],n,o.D.spa,p),function(){if(m.emit((i?"":"no-")+"fn-start",[(0,d.z)(),n,i],r),i)try{return t.apply(this,arguments)}catch(e){throw m.emit("fn-err",[arguments,this,"string"==typeof e?new Error(e):e],r),e}finally{m.emit("fn-end",[(0,d.z)()],r)}}}};function x(e,t,r,n){return function(){return(0,s.p)(h.xS,["API/"+t+"/called"],void 0,o.D.metrics,p),(0,s.p)(e+t,[(0,d.z)()].concat(i()(arguments)),r?null:this,n,p),r?void 0:this}}function j(){r.e(439).then(r.bind(r,5692)).then((t=>{let{setAPI:r}=t;r(e),(0,f.L)(e,"api")})).catch((()=>(0,v.Z)("Downloading runtime APIs failed...")))}return(0,c.D)("actionText,setName,setAttribute,save,ignore,onEnd,getContext,end,get".split(","),(function(e,t){A[t]=x(w,t,void 0,o.D.spa)})),n.noticeError=function(e,t){"string"==typeof e&&(e=new Error(e)),(0,s.p)(h.xS,["API/noticeError/called"],void 0,o.D.metrics,p),(0,s.p)("err",[e,(0,d.z)(),!1,t],void 0,o.D.jserrors,p)},g.v6?j():(0,l.b)((()=>j()),!0),n}(e,y);return(0,p.Qy)(e,k,"api"),(0,p.Qy)(e,E,"exposed"),(0,p.EZ)("activatedFeatures",b),(0,p.EZ)("setToken",(t=>function(e,t){var r=u.ee.get(t);e&&"object"==typeof e&&((0,c.D)(e,(function(e,t){if(!t)return(m[e]||[]).forEach((t=>{(0,s.p)("block-"+e,[],void 0,t,r)}));b[e]||((0,s.p)("feat-"+e,[],void 0,m[e],r),b[e]=!0)})),(0,f.L)(t,o.D.pageViewEvent))}(t,e))),k}},909:(e,t,r)=>{"use strict";r.d(t,{Z:()=>i,q:()=>o});var n=r(2325);function i(e){switch(e){case n.D.ajax:return[n.D.jserrors];case n.D.sessionTrace:return[n.D.ajax,n.D.pageViewEvent];case n.D.pageViewTiming:return[n.D.pageViewEvent];default:return[]}}function o(e){return e===n.D.jserrors?[]:["auto"]}},2325:(e,t,r)=>{"use strict";r.d(t,{D:()=>n,p:()=>i});const n={ajax:"ajax",jserrors:"jserrors",metrics:"metrics",pageAction:"page_action",pageViewEvent:"page_view_event",pageViewTiming:"page_view_timing",sessionTrace:"session_trace",spa:"spa"},i={[n.pageViewEvent]:1,[n.pageViewTiming]:2,[n.metrics]:3,[n.jserrors]:4,[n.ajax]:5,[n.sessionTrace]:6,[n.pageAction]:7,[n.spa]:8}},8683:e=>{e.exports=function(e,t,r){t||(t=0),void 0===r&&(r=e?e.length:0);for(var n=-1,i=r-t||0,o=Array(i<0?0:i);++n<i;)o[n]=e[t+n];return o}}},n={};function i(e){var t=n[e];if(void 0!==t)return t.exports;var o=n[e]={exports:{}};return r[e](o,o.exports,i),o.exports}i.m=r,i.n=e=>{var t=e&&e.__esModule?()=>e.default:()=>e;return i.d(t,{a:t}),t},i.d=(e,t)=>{for(var r in t)i.o(t,r)&&!i.o(e,r)&&Object.defineProperty(e,r,{enumerable:!0,get:t[r]})},i.f={},i.e=e=>Promise.all(Object.keys(i.f).reduce(((t,r)=>(i.f[r](e,t),t)),[])),i.u=e=>(({78:"page_action-aggregate",147:"metrics-aggregate",193:"session_trace-aggregate",317:"jserrors-aggregate",348:"page_view_timing-aggregate",439:"async-api",729:"lazy-loader",786:"page_view_event-aggregate",873:"spa-aggregate",898:"ajax-aggregate"}[e]||e)+"."+{78:"8658345c",147:"fde0a6c6",193:"afe7d95b",317:"265ba41e",348:"92e7c907",439:"71768fc8",729:"ff971c03",786:"a968183b",862:"5040a0e9",873:"6a952689",898:"ebcbd305"}[e]+"-1.229.0.min.js"),i.o=(e,t)=>Object.prototype.hasOwnProperty.call(e,t),e={},t="NRBA:",i.l=(r,n,o,a)=>{if(e[r])e[r].push(n);else{var s,c;if(void 0!==o)for(var u=document.getElementsByTagName("script"),d=0;d<u.length;d++){var f=u[d];if(f.getAttribute("src")==r||f.getAttribute("data-webpack")==t+o){s=f;break}}s||(c=!0,(s=document.createElement("script")).charset="utf-8",s.timeout=120,i.nc&&s.setAttribute("nonce",i.nc),s.setAttribute("data-webpack",t+o),s.src=r),e[r]=[n];var l=(t,n)=>{s.onerror=s.onload=null,clearTimeout(g);var i=e[r];if(delete e[r],s.parentNode&&s.parentNode.removeChild(s),i&&i.forEach((e=>e(n))),t)return t(n)},g=setTimeout(l.bind(null,void 0,{type:"timeout",target:s}),12e4);s.onerror=l.bind(null,s.onerror),s.onload=l.bind(null,s.onload),c&&document.head.appendChild(s)}},i.r=e=>{"undefined"!=typeof Symbol&&Symbol.toStringTag&&Object.defineProperty(e,Symbol.toStringTag,{value:"Module"}),Object.defineProperty(e,"__esModule",{value:!0})},i.p="https://js-agent.newrelic.com/",(()=>{var e={521:0,38:0};i.f.j=(t,r)=>{var n=i.o(e,t)?e[t]:void 0;if(0!==n)if(n)r.push(n[2]);else{var o=new Promise(((r,i)=>n=e[t]=[r,i]));r.push(n[2]=o);var a=i.p+i.u(t),s=new Error;i.l(a,(r=>{if(i.o(e,t)&&(0!==(n=e[t])&&(e[t]=void 0),n)){var o=r&&("load"===r.type?"missing":r.type),a=r&&r.target&&r.target.src;s.message="Loading chunk "+t+" failed.\n("+o+": "+a+")",s.name="ChunkLoadError",s.type=o,s.request=a,n[1](s)}}),"chunk-"+t,t)}};var t=(t,r)=>{var n,o,[a,s,c]=r,u=0;if(a.some((t=>0!==e[t]))){for(n in s)i.o(s,n)&&(i.m[n]=s[n]);if(c)c(i)}for(t&&t(r);u<a.length;u++)o=a[u],i.o(e,o)&&e[o]&&e[o][0](),e[o]=0},r=window.webpackChunkNRBA=window.webpackChunkNRBA||[];r.forEach(t.bind(null,0)),r.push=t.bind(null,r.push.bind(r))})();var o={};(()=>{"use strict";i.r(o);var e=i(2325),t=i(6562);const r=Object.values(e.D);function n(e){const n={};return r.forEach((r=>{n[r]=function(e,r){return!1!==(0,t.Mt)(r,"".concat(e,".enabled"))}(r,e)})),n}var a=i(5432),s=i(909),c=i(9252),u=i(8768),d=i(4329),f=i(1509),l=i(2650),g=i(2374),v=i(8610);class h extends f.W{constructor(e,t,r){let n=!(arguments.length>3&&void 0!==arguments[3])||arguments[3];super(e,t,r),this.hasAggregator=!1,this.auto=n,this.abortHandler,n&&(0,d.R)(e,r)}importAggregator(){if(this.hasAggregator||!this.auto)return;this.hasAggregator=!0;const e=async()=>{try{const{lazyLoader:e}=await i.e(729).then(i.bind(i,8110)),{Aggregate:t}=await e(this.featureName,"aggregate");new t(this.agentIdentifier,this.aggregator)}catch(e){(0,v.Z)("Downloading ".concat(this.featureName," failed...")),this.abortHandler?.()}};g.v6?e():(0,l.b)((()=>e()),!0)}}var p,m,b,w=i(2484),y=i(2053);class A extends h{constructor(r,n){let i=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];if(super(r,n,w.t9,i),("undefined"==typeof PerformanceNavigationTiming||u.T)&&"undefined"!=typeof PerformanceTiming){const n=(0,t.OP)(r);n[w.Dz]=Math.max(Date.now()-n.offset,0),(0,l.K)((()=>n[w.qw]=Math.max((0,y.z)()-n[w.Dz],0))),(0,l.b)((()=>{const t=(0,y.z)();n[w.OJ]=Math.max(t-n[w.Dz],0),(0,c.p)("timing",["load",t],void 0,e.D.pageViewTiming,this.ee)}))}this.importAggregator()}}p=A,m="featureName",b=w.t9,(m=function(e){var t=function(e,t){if("object"!=typeof e||null===e)return e;var r=e[Symbol.toPrimitive];if(void 0!==r){var n=r.call(e,t||"default");if("object"!=typeof n)return n;throw new TypeError("@@toPrimitive must return a primitive value.")}return("string"===t?String:Number)(e)}(e,"string");return"symbol"==typeof t?t:String(t)}(m))in p?Object.defineProperty(p,m,{value:b,enumerable:!0,configurable:!0,writable:!0}):p[m]=b;var x=i(9557),j=i(7022);class _ extends x.w{constructor(e){super(e),this.aggregatedData={}}store(e,t,r,n,i){var o=this.getBucket(e,t,r,i);return o.metrics=function(e,t){t||(t={count:0});return t.count+=1,(0,j.D)(e,(function(e,r){t[e]=E(r,t[e])})),t}(n,o.metrics),o}merge(e,t,r,n,i){var o=this.getBucket(e,t,n,i);if(o.metrics){var a=o.metrics;a.count+=r.count,(0,j.D)(r,(function(e,t){if("count"!==e){var n=a[e],i=r[e];i&&!i.c?a[e]=E(i.t,n):a[e]=function(e,t){if(!t)return e;t.c||(t=D(t.t));return t.min=Math.min(e.min,t.min),t.max=Math.max(e.max,t.max),t.t+=e.t,t.sos+=e.sos,t.c+=e.c,t}(i,a[e])}}))}else o.metrics=r}storeMetric(e,t,r,n){var i=this.getBucket(e,t,r);return i.stats=E(n,i.stats),i}getBucket(e,t,r,n){this.aggregatedData[e]||(this.aggregatedData[e]={});var i=this.aggregatedData[e][t];return i||(i=this.aggregatedData[e][t]={params:r||{}},n&&(i.custom=n)),i}get(e,t){return t?this.aggregatedData[e]&&this.aggregatedData[e][t]:this.aggregatedData[e]}take(e){for(var t={},r="",n=!1,i=0;i<e.length;i++)t[r=e[i]]=k(this.aggregatedData[r]),t[r].length&&(n=!0),delete this.aggregatedData[r];return n?t:null}}function E(e,t){return null==e?function(e){e?e.c++:e={c:1};return e}(t):t?(t.c||(t=D(t.t)),t.c+=1,t.t+=e,t.sos+=e*e,e>t.max&&(t.max=e),e<t.min&&(t.min=e),t):{t:e}}function D(e){return{t:e,min:e,max:e,sos:e*e,c:1}}function k(e){return"object"!=typeof e?[]:(0,j.D)(e,S)}function S(e,t){return t}var P=i(6797),T=i(5526),N=i(2438);var O=i(6998),I=i(8544),C=i(6382);class R extends h{constructor(e,r){let n=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(e,r,C.t,n),g.il&&((0,t.OP)(e).initHidden=Boolean("hidden"===document.visibilityState),(0,O.N)((()=>(0,c.p)("docHidden",[(0,y.z)()],void 0,C.t,this.ee)),!0),(0,I.bP)("pagehide",(()=>(0,c.p)("winPagehide",[(0,y.z)()],void 0,C.t,this.ee))),this.importAggregator())}}!function(e,t,r){(t=function(e){var t=function(e,t){if("object"!=typeof e||null===e)return e;var r=e[Symbol.toPrimitive];if(void 0!==r){var n=r.call(e,t||"default");if("object"!=typeof n)return n;throw new TypeError("@@toPrimitive must return a primitive value.")}return("string"===t?String:Number)(e)}(e,"string");return"symbol"==typeof t?t:String(t)}(t))in e?Object.defineProperty(e,t,{value:r,enumerable:!0,configurable:!0,writable:!0}):e[t]=r}(R,"featureName",C.t);const M=Boolean(g._A?.Worker),z=Boolean(g._A?.SharedWorker),B=Boolean(g._A?.navigator?.serviceWorker);let q,W,V;var L=i(6034);class Z extends h{constructor(t,r){let n=!(arguments.length>2&&void 0!==arguments[2])||arguments[2];super(t,r,L.t9,n),function(e){if(!q){if(M){q=Worker;try{g._A.Worker=r(q,"Dedicated")}catch(e){o(e,"Dedicated")}if(z){W=SharedWorker;try{g._A.SharedWorker=r(W,"Shared")}catch(e){o(e,"Shared")}}else n("Shared");if(B){V=navigator.serviceWorker.register;try{g._A.navigator.serviceWorker.register=(t=V,function(){for(var e=arguments.length,r=new Array(e),n=0;n<e;n++)r[n]=arguments[n];return i("Service",r[1]?.type),t.apply(navigator.serviceWorker,r)})}catch(e){o(e,"Service")}}else n("Service");var t;return}n("All")}function r(e,t){return"undefined"==typeof Proxy?e:new Proxy(e,{construct:(e,r)=>(i(t,r[1]?.type),new e(...r))})}function n(t){g.v6||e("Workers/".concat(t,"/Unavailable"))}function i(t,r){e("Workers/".concat(t,"module"===r?"/Module":"/Classic"))}function o(t,r){e("Workers/".concat(r,"/SM/Unsupported")),(0,v.Z)("NR Agent: Unable to capture ".concat(r," workers."),t)}}((t=>(0,c.p)(L.xS,[t],void 0,e.D.metrics,this.ee))),this.importAggregator()}}!function(e,t,r){(t=function(e){var t=function(e,t){if("object"!=typeof e||null===e)return e;var r=e[Symbol.toPrimitive];if(void 0!==r){var n=r.call(e,t||"default");if("object"!=typeof n)return n;throw new TypeError("@@toPrimitive must return a primitive value.")}return("string"===t?String:Number)(e)}(e,"string");return"symbol"==typeof t?t:String(t)}(t))in e?Object.defineProperty(e,t,{value:r,enumerable:!0,configurable:!0,writable:!0}):e[t]=r}(Z,"featureName",L.t9),new class{constructor(e){let t=arguments.length>1&&void 0!==arguments[1]?arguments[1]:(0,T.ky)(16);this.agentIdentifier=t,this.sharedAggregator=new _({agentIdentifier:this.agentIdentifier}),this.features={},this.desiredFeatures=new Set(e.features||[]),this.desiredFeatures.add(A),Object.assign(this,(0,a.j)(this.agentIdentifier,e,e.loaderType||"agent")),this.start()}get config(){return{info:(0,t.C5)(this.agentIdentifier),init:(0,t.P_)(this.agentIdentifier),loader_config:(0,t.DL)(this.agentIdentifier),runtime:(0,t.OP)(this.agentIdentifier)}}start(){const t="features";try{const r=n(this.agentIdentifier),i=Array.from(this.desiredFeatures);i.sort(((t,r)=>e.p[t.featureName]-e.p[r.featureName])),i.forEach((t=>{if(r[t.featureName]||t.featureName===e.D.pageViewEvent){const e=(0,s.Z)(t.featureName);e.every((e=>r[e]))||(0,v.Z)("".concat(t.featureName," is enabled but one or more dependent features has been disabled (").concat((0,N.P)(e),"). This may cause unintended consequences or missing data...")),this.features[t.featureName]=new t(this.agentIdentifier,this.sharedAggregator)}})),(0,P.Qy)(this.agentIdentifier,this.features,t)}catch(e){(0,v.Z)("Failed to initialize all enabled instrument classes (agent aborted) -",e);for(const e in this.features)this.features[e].abortHandler?.();const r=(0,P.fP)();return delete r.initializedAgents[this.agentIdentifier]?.api,delete r.initializedAgents[this.agentIdentifier]?.[t],delete this.sharedAggregator,r.ee?.abort(),delete r.ee?.get(this.agentIdentifier),!1}}}({features:[A,R,Z],loaderType:"lite"})})(),window.NRBA=o})();</script>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
      <meta name="twitter:card"  content="summary_large_image" />
      <meta name="twitter:site"  content="@AdobePortfolio" />
      <meta  property="og:title" content="竹篦舎 -TAKENOYA-" />
      <meta  property="og:image" content="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dfdddd88-11db-4107-9636-831dfc13f3ef_rwc_0x0x2158x1520x2158.png?h=b442641bf2309883524934d6deba364f" />
      <link rel="icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQAQMAAAAlPW0iAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAADUExURUxpcU3H2DoAAAABdFJOUwBA5thmAAAADElEQVQI12NgIA0AAAAwAAHHqoWOAAAAAElFTkSuQmCC"  />
      <link rel="stylesheet" href="/dist/css/main.css" type="text/css" />
      <link rel="stylesheet" href="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/08c26634df215e2d1afdb783e2ca11d51678050910.css?h=f330f883a2e4369850ab423511e90403" type="text/css" />
    <link rel="canonical" href="https://takenoya.myportfolio.com/home" />
      <title>竹篦舎 -TAKENOYA-</title>
    <script type="text/javascript" src="//use.typekit.net/ik/B9mSgM2bUlJHekf6iRjH4H4lW4bTtUvKAHzhP1Xzou9fenwgfHYEBsJzwD9oFDIDWhjoFDiy5Q4qweFRwRwojDMuFRJhwQscwhs8wQMowRZyZcjuFhbkwhI-mkG0dW83da4XZcNC-Av0jhNlOfG0SY4zwKuh-AmaOcuoSeNkieZzde8zOcFzdPUlpWgzS1scdhUTdkoRdhXCSY4zwKuh-AmaOcuoSeNkieZzde8zOcFzdPJIjcT3ZkGHfH_JMsMMeMb6MKGHfHDJMsMMeMS6MTMga0_BtM9.js?cb=8b765f26b47d810cfbc3804118a98ceaac9a7a0c" async onload="
    try {
      window.Typekit.load();
    } catch (e) {
      console.warn('Typekit not loaded.');
    }
    "></script>
</head>
  <body class="transition-enabled">    <section class="splash centered e2e-site-content">
      <div class="outer-wrap">
        <div class="centered-content-wrap js-site-wrap splash-modules">
      <div class='page-background-video page-background-video-with-panel'>
      </div>
      <div class="page-content js-page-content" data-context="pages" data-identity="id:p6402450ed31b0159327d8247a7ec140e68efd61695847201388dd">
        <div id="project-canvas" class="js-project-modules modules content">
          <div id="project-modules">
              
              
              
              
              
              <div class="project-module module text project-module-text align- js-project-module e2e-site-project-module-text">
  <div class="rich-text js-text-editable module-text"><div class="title">竹篦舎 -TAKENOYA-</div></div>
</div>

              
              
              
              
              
              
              
              
              
              <div class="project-module module text project-module-text align- js-project-module e2e-site-project-module-text" style="padding-top: 13px;
padding-bottom: 0px;
">
  <div class="rich-text js-text-editable module-text"><div><span style="font-size:22px;" class="texteditor-inline-fontsize">原　良輔 / Ryosuke HARA</span></div></div>
</div>

              
              
              
              
              
              
              
              
              
              <div class="project-module module text project-module-text align- js-project-module e2e-site-project-module-text" style="padding-top: 0px;
padding-bottom: 0px;
  max-width: 800px;
">
  <div class="rich-text js-text-editable module-text"><div style="line-height:14px;" class="texteditor-inline-lineheight"><span style="font-size:12px;" class="texteditor-inline-fontsize"> 九州大学大学院　人間環境学府・空間システム専攻　末廣研究室<br>SUEHIRO lab, Graduate School of Human-Environment Studies, Kyushu University</span></div></div>
</div>

              
              
              
              
              <div class="js-project-module project-module module button project-module-button" data-id="m6402450ed571b3106282b09217080e60c35b983ed34962bfb2b83"  style=" padding-top: 15px;
padding-bottom: 25px;
">
    <div class="button-container" style="">
      
      <a href="https://indd.adobe.com/view/fc78ee5c-2f22-42ca-80c1-8f91c37cf7af" target="_blank" class="button-module preserve-whitespace--nowrap">Read the Full version</a>
    </div>
</div>

              
              
              
              
              
              
              
              
              
              
              
              
              
              
              <div class="project-module module text project-module-text align- js-project-module e2e-site-project-module-text" style="padding-top: px;
padding-bottom: px;
  float: right;
  clear: both;
">
  <div class="rich-text js-text-editable module-text"><div style="line-height:14px;text-align:right;" class="texteditor-inline-lineheight"><span class="texteditor-inline-fontsize" style="font-size:12px;">Editorial design : Kazuki FUJII <br>(MSc in Communication Sciences in Digital Media and Society, KU Leuven in Belgium)</span></div></div>
</div>

              
              
              
              
              
              
              
              
              
              
              
              <div class="project-module module media_collection project-module-media_collection" data-id="m6403467e5a621494b522f6f70ae15cea2194ca9716dc7d2c3ca15"  style="padding-top: px;
padding-bottom: px;
">
  <div class="grid--main js-grid-main" data-grid-max-images="  4
">
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1920.jpg?h=6b19274f3692f90c89b91bebfad11728" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_600.jpg?h=c6350e56bee27b86f78e3cf4b373645e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1200.jpg?h=47c193620b20f94ff27ce5b497496784 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1920.jpg?h=6b19274f3692f90c89b91bebfad11728 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1920.jpg?h=6b19274f3692f90c89b91bebfad11728"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_600.jpg?h=c6350e56bee27b86f78e3cf4b373645e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1200.jpg?h=47c193620b20f94ff27ce5b497496784 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4ef15169-0c30-42a1-9ff9-51047efd635c_rw_1920.jpg?h=6b19274f3692f90c89b91bebfad11728 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1920.jpg?h=9b36d9e4e69693aed1dc06ca9a5619e8" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_600.jpg?h=27453e24b7803e86943c076c322e8613 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1200.jpg?h=991f5e8bff2766a532631cc3a69c31dc 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1920.jpg?h=9b36d9e4e69693aed1dc06ca9a5619e8 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1920.jpg?h=9b36d9e4e69693aed1dc06ca9a5619e8"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_600.jpg?h=27453e24b7803e86943c076c322e8613 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1200.jpg?h=991f5e8bff2766a532631cc3a69c31dc 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e2c3b2f2-ca99-4c69-9384-bec5f3d9ae7d_rw_1920.jpg?h=9b36d9e4e69693aed1dc06ca9a5619e8 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1920.jpg?h=e987a9a4a9cbad98bbec870d873600f8" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_600.jpg?h=d0559a389c88ed1e689afe1df4853646 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1200.jpg?h=43e63c37428310e655cdc6630f1be4e9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1920.jpg?h=e987a9a4a9cbad98bbec870d873600f8 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1920.jpg?h=e987a9a4a9cbad98bbec870d873600f8"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_600.jpg?h=d0559a389c88ed1e689afe1df4853646 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1200.jpg?h=43e63c37428310e655cdc6630f1be4e9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/d8e95bfd-c380-4055-be93-1f57a575de2e_rw_1920.jpg?h=e987a9a4a9cbad98bbec870d873600f8 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1920.jpg?h=3b613ab0d1c23d6a368993614ead2934" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_600.jpg?h=20a4c071426bf14fc9bd4b04cccc34d5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1200.jpg?h=a93fcf946baebb089020defe24d1635a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1920.jpg?h=3b613ab0d1c23d6a368993614ead2934 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1920.jpg?h=3b613ab0d1c23d6a368993614ead2934"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_600.jpg?h=20a4c071426bf14fc9bd4b04cccc34d5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1200.jpg?h=a93fcf946baebb089020defe24d1635a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/146f51f9-3128-4fff-a200-f4e057addcca_rw_1920.jpg?h=3b613ab0d1c23d6a368993614ead2934 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1920.jpg?h=4f9c078cc7a2d96f1e129aee74c75281" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_600.jpg?h=b4d2f1cad41bac8f7ae078b410144713 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1200.jpg?h=71d235ee372e7bd3541acdd49b936d71 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1920.jpg?h=4f9c078cc7a2d96f1e129aee74c75281 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1920.jpg?h=4f9c078cc7a2d96f1e129aee74c75281"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_600.jpg?h=b4d2f1cad41bac8f7ae078b410144713 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1200.jpg?h=71d235ee372e7bd3541acdd49b936d71 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ce4c93ba-be8b-45c7-a268-dc6188ba728e_rw_1920.jpg?h=4f9c078cc7a2d96f1e129aee74c75281 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1920.jpg?h=3e70c90f6e86468ee78053fb040659c4" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_600.jpg?h=be0e198f6e0d568e422ca285198dc62b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1200.jpg?h=d2648e889638b6b5a5162ead37429b16 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1920.jpg?h=3e70c90f6e86468ee78053fb040659c4 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1920.jpg?h=3e70c90f6e86468ee78053fb040659c4"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_600.jpg?h=be0e198f6e0d568e422ca285198dc62b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1200.jpg?h=d2648e889638b6b5a5162ead37429b16 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/0486e176-2f91-48ac-9693-aa5e97261c31_rw_1920.jpg?h=3e70c90f6e86468ee78053fb040659c4 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1920.jpg?h=6cd1415e082c4a17bf0d2aefffb0341b" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_600.jpg?h=7e5bce4c44098f821c933e02c9906fd3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1200.jpg?h=bbc17e0619e44502d07fc61dfbcae0bd 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1920.jpg?h=6cd1415e082c4a17bf0d2aefffb0341b 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1920.jpg?h=6cd1415e082c4a17bf0d2aefffb0341b"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_600.jpg?h=7e5bce4c44098f821c933e02c9906fd3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1200.jpg?h=bbc17e0619e44502d07fc61dfbcae0bd 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ae66dfe4-23d1-487f-81c5-9e1f117f1402_rw_1920.jpg?h=6cd1415e082c4a17bf0d2aefffb0341b 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1920.jpg?h=1f0c9d07b484de689ade9f33f17d5a95" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_600.jpg?h=0e320b326570c6af784f215200c5bb46 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1200.jpg?h=983e465d5586803c55a2430d4b4f1e57 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1920.jpg?h=1f0c9d07b484de689ade9f33f17d5a95 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1920.jpg?h=1f0c9d07b484de689ade9f33f17d5a95"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_600.jpg?h=0e320b326570c6af784f215200c5bb46 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1200.jpg?h=983e465d5586803c55a2430d4b4f1e57 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c9249d44-14ba-4cc6-a9f2-597d4ae4fb00_rw_1920.jpg?h=1f0c9d07b484de689ade9f33f17d5a95 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1920.jpg?h=30b4868e5250f99cf6e3cf45a2f460ae" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_600.jpg?h=b7a04b5b4c1b89dd435b7bb62eee6810 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1200.jpg?h=cef79c1f061b9979453d9c03f8b304f9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1920.jpg?h=30b4868e5250f99cf6e3cf45a2f460ae 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1920.jpg?h=30b4868e5250f99cf6e3cf45a2f460ae"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_600.jpg?h=b7a04b5b4c1b89dd435b7bb62eee6810 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1200.jpg?h=cef79c1f061b9979453d9c03f8b304f9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bb1475a-dbc1-45f2-9ccc-e3ba954193b9_rw_1920.jpg?h=30b4868e5250f99cf6e3cf45a2f460ae 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1920.jpg?h=b2df56d38fb98f76e85524104289bc4c" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_600.jpg?h=80ad45d4a5a08709bb473e2aa373a05b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1200.jpg?h=a7ec846ecf0c73bce2e097d5f4499b56 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1920.jpg?h=b2df56d38fb98f76e85524104289bc4c 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1920.jpg?h=b2df56d38fb98f76e85524104289bc4c"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_600.jpg?h=80ad45d4a5a08709bb473e2aa373a05b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1200.jpg?h=a7ec846ecf0c73bce2e097d5f4499b56 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6f3c4f49-6505-4f56-88ea-bc6898fa30fd_rw_1920.jpg?h=b2df56d38fb98f76e85524104289bc4c 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1920.jpg?h=47582cb5d7902ca0920ec9575149d68e" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_600.jpg?h=2342fc7ea60b92c0be7459554af0d511 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1200.jpg?h=6c8d22ebe3e0ca70bd918d1ffb8c6063 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1920.jpg?h=47582cb5d7902ca0920ec9575149d68e 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1920.jpg?h=47582cb5d7902ca0920ec9575149d68e"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_600.jpg?h=2342fc7ea60b92c0be7459554af0d511 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1200.jpg?h=6c8d22ebe3e0ca70bd918d1ffb8c6063 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/dce27ea1-b9a8-4080-9155-ed10474d9ea4_rw_1920.jpg?h=47582cb5d7902ca0920ec9575149d68e 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1920.jpg?h=17ce8db2ebfc60e13bfae0d2398b815f" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_600.jpg?h=9cb6b079863b36299816e05487de3fd9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1200.jpg?h=5358cd6fac74744b5b3a0d6a1eb216e6 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1920.jpg?h=17ce8db2ebfc60e13bfae0d2398b815f 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1920.jpg?h=17ce8db2ebfc60e13bfae0d2398b815f"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_600.jpg?h=9cb6b079863b36299816e05487de3fd9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1200.jpg?h=5358cd6fac74744b5b3a0d6a1eb216e6 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f41a1006-f0f7-4696-a29b-43a623159383_rw_1920.jpg?h=17ce8db2ebfc60e13bfae0d2398b815f 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1920.jpg?h=551d302120be8c9d15f35045ab456202" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_600.jpg?h=ac3b0d7c193ef44cfcf4cd3ee645d677 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1200.jpg?h=a1b028cb53dbadb5d53845a31657f235 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1920.jpg?h=551d302120be8c9d15f35045ab456202 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1920.jpg?h=551d302120be8c9d15f35045ab456202"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_600.jpg?h=ac3b0d7c193ef44cfcf4cd3ee645d677 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1200.jpg?h=a1b028cb53dbadb5d53845a31657f235 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4771ceb3-9b00-41a4-a9a3-52d9805b9862_rw_1920.jpg?h=551d302120be8c9d15f35045ab456202 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1920.jpg?h=1d9d9f5453139c1f9a78f2c89c2cd8e8" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_600.jpg?h=2625e58683b6d374b59a91c4537ed07d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1200.jpg?h=6d9db2dc92fbd83521129d77eb73ec56 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1920.jpg?h=1d9d9f5453139c1f9a78f2c89c2cd8e8 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1920.jpg?h=1d9d9f5453139c1f9a78f2c89c2cd8e8"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_600.jpg?h=2625e58683b6d374b59a91c4537ed07d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1200.jpg?h=6d9db2dc92fbd83521129d77eb73ec56 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e6e84052-1182-4abc-9631-bb8e465b7381_rw_1920.jpg?h=1d9d9f5453139c1f9a78f2c89c2cd8e8 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1920.jpg?h=6744ec8693fd9091ae0c464d9b51abfd" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_600.jpg?h=89c0d772319ade0607bfc7a0964e5dd2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1200.jpg?h=b44942c5c3dbfa885e579e03a6253768 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1920.jpg?h=6744ec8693fd9091ae0c464d9b51abfd 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1920.jpg?h=6744ec8693fd9091ae0c464d9b51abfd"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_600.jpg?h=89c0d772319ade0607bfc7a0964e5dd2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1200.jpg?h=b44942c5c3dbfa885e579e03a6253768 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/85ba9103-59e6-4481-9f0e-e7a4b418b667_rw_1920.jpg?h=6744ec8693fd9091ae0c464d9b51abfd 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1920.jpg?h=1b8cc40defae91cd06a2cb6ac88e40f0" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_600.jpg?h=70eda9e9ce0ac6ba46ffac92c1eee3a3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1200.jpg?h=fcceb4d956821f212c1d7056b41ecfea 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1920.jpg?h=1b8cc40defae91cd06a2cb6ac88e40f0 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1920.jpg?h=1b8cc40defae91cd06a2cb6ac88e40f0"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_600.jpg?h=70eda9e9ce0ac6ba46ffac92c1eee3a3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1200.jpg?h=fcceb4d956821f212c1d7056b41ecfea 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c004a2b6-488b-47cc-95fa-ebc22b2581c6_rw_1920.jpg?h=1b8cc40defae91cd06a2cb6ac88e40f0 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1920.jpg?h=339b4fd4533eba164bc8bc54529d2a6c" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_600.jpg?h=35bdf5e8bd74f39018f341a460b07bac 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1200.jpg?h=c0e08372326caf5ec254a2f7875fea41 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1920.jpg?h=339b4fd4533eba164bc8bc54529d2a6c 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1920.jpg?h=339b4fd4533eba164bc8bc54529d2a6c"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_600.jpg?h=35bdf5e8bd74f39018f341a460b07bac 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1200.jpg?h=c0e08372326caf5ec254a2f7875fea41 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/30376358-7419-48ad-8328-a706902ca9bd_rw_1920.jpg?h=339b4fd4533eba164bc8bc54529d2a6c 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1920.jpg?h=1aae67effd6719028c9f67b980499baf" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_600.jpg?h=96e51d7b46fea8d5cc9e73e629da1102 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1200.jpg?h=b33fc171fb64517f9056fc4d969271bb 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1920.jpg?h=1aae67effd6719028c9f67b980499baf 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1920.jpg?h=1aae67effd6719028c9f67b980499baf"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_600.jpg?h=96e51d7b46fea8d5cc9e73e629da1102 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1200.jpg?h=b33fc171fb64517f9056fc4d969271bb 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4713bd3d-f6e0-4815-9839-2c51cfaa46da_rw_1920.jpg?h=1aae67effd6719028c9f67b980499baf 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1920.jpg?h=799760b4e7811f4d4ff8968853ac47af" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_600.jpg?h=9b8faaafc21f2c5e1ed835dc0847ee90 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1200.jpg?h=bbceaead26ad5c8b4f9baec64fb115c1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1920.jpg?h=799760b4e7811f4d4ff8968853ac47af 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1920.jpg?h=799760b4e7811f4d4ff8968853ac47af"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_600.jpg?h=9b8faaafc21f2c5e1ed835dc0847ee90 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1200.jpg?h=bbceaead26ad5c8b4f9baec64fb115c1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/49812f13-44b2-47a0-be21-52b377fe1e9b_rw_1920.jpg?h=799760b4e7811f4d4ff8968853ac47af 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1920.jpg?h=4d0409d9c2a6963c7e8972ce693acc46" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_600.jpg?h=92e1e2dee161020a23ea7361731a8bc9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1200.jpg?h=cc944a2fd2b95175b0463ba1efcd46d9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1920.jpg?h=4d0409d9c2a6963c7e8972ce693acc46 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1920.jpg?h=4d0409d9c2a6963c7e8972ce693acc46"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_600.jpg?h=92e1e2dee161020a23ea7361731a8bc9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1200.jpg?h=cc944a2fd2b95175b0463ba1efcd46d9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c690679d-4736-42fc-b835-1b55447f33e4_rw_1920.jpg?h=4d0409d9c2a6963c7e8972ce693acc46 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1920.jpg?h=365789d70d74e3a18869c0af73cd39e6" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_600.jpg?h=e6ab300e1deeeb19cdc42018dab81634 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1200.jpg?h=d546143033c14e071254d823c0a4a941 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1920.jpg?h=365789d70d74e3a18869c0af73cd39e6 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1920.jpg?h=365789d70d74e3a18869c0af73cd39e6"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_600.jpg?h=e6ab300e1deeeb19cdc42018dab81634 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1200.jpg?h=d546143033c14e071254d823c0a4a941 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9ff0f910-8936-4403-9d18-3f6403a4838a_rw_1920.jpg?h=365789d70d74e3a18869c0af73cd39e6 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1920.jpg?h=22b3e5fc7bcef4e9f65cf235d5982573" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_600.jpg?h=df57e2ae1d2f24acb9cd819ab85debc4 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1200.jpg?h=f3837391ee614bd5fec092424fa480f5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1920.jpg?h=22b3e5fc7bcef4e9f65cf235d5982573 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1920.jpg?h=22b3e5fc7bcef4e9f65cf235d5982573"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_600.jpg?h=df57e2ae1d2f24acb9cd819ab85debc4 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1200.jpg?h=f3837391ee614bd5fec092424fa480f5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/344d619c-b0cc-40ae-87a4-18393bc71da5_rw_1920.jpg?h=22b3e5fc7bcef4e9f65cf235d5982573 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1920.jpg?h=a9f9b564c7294456ebf036cf334e451b" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_600.jpg?h=a07d31ffade5566be44035ad8193cedb 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1200.jpg?h=80b20a2337109b362663a43ddaab1467 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1920.jpg?h=a9f9b564c7294456ebf036cf334e451b 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1920.jpg?h=a9f9b564c7294456ebf036cf334e451b"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_600.jpg?h=a07d31ffade5566be44035ad8193cedb 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1200.jpg?h=80b20a2337109b362663a43ddaab1467 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/50cafa60-b157-411d-8788-2d006bd4c82e_rw_1920.jpg?h=a9f9b564c7294456ebf036cf334e451b 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1920.jpg?h=83f956f20feda19b38ae41c07f982cf9" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_600.jpg?h=61d7f160831a34e6d13db0a986c720e3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1200.jpg?h=366cc1704dee22004010e6ddf1b0d6cf 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1920.jpg?h=83f956f20feda19b38ae41c07f982cf9 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1920.jpg?h=83f956f20feda19b38ae41c07f982cf9"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_600.jpg?h=61d7f160831a34e6d13db0a986c720e3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1200.jpg?h=366cc1704dee22004010e6ddf1b0d6cf 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3f7d0a26-c9e6-43df-a1c5-b612cc047c6a_rw_1920.jpg?h=83f956f20feda19b38ae41c07f982cf9 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1920.jpg?h=08e8ffe3715aef78efae2954aa7a7d06" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_600.jpg?h=44bb7e95679ea21a936d0609400783c2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1200.jpg?h=4959399ab639feede1272fbb30cfb96f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1920.jpg?h=08e8ffe3715aef78efae2954aa7a7d06 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1920.jpg?h=08e8ffe3715aef78efae2954aa7a7d06"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_600.jpg?h=44bb7e95679ea21a936d0609400783c2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1200.jpg?h=4959399ab639feede1272fbb30cfb96f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/6537cd7d-17ae-4cfd-acd0-2a69f65f4b12_rw_1920.jpg?h=08e8ffe3715aef78efae2954aa7a7d06 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1920.jpg?h=cb3a4a7dc9d1c05ef811804bcd652ad0" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_600.jpg?h=bfd1307f371ef6dfe35c10fd496264ef 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1200.jpg?h=2b2b1c2544d546462c7c16231f4d1e86 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1920.jpg?h=cb3a4a7dc9d1c05ef811804bcd652ad0 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1920.jpg?h=cb3a4a7dc9d1c05ef811804bcd652ad0"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_600.jpg?h=bfd1307f371ef6dfe35c10fd496264ef 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1200.jpg?h=2b2b1c2544d546462c7c16231f4d1e86 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c2ca2f10-5ca3-41a5-9e8e-5302e8e23e39_rw_1920.jpg?h=cb3a4a7dc9d1c05ef811804bcd652ad0 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1920.jpg?h=eb82e0c7ed1d930e4ffd1c0523c3d502" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_600.jpg?h=8143763da4ec9398520fbc798e3eadc5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1200.jpg?h=daef85522def3d16302087df0e4303a8 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1920.jpg?h=eb82e0c7ed1d930e4ffd1c0523c3d502 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1920.jpg?h=eb82e0c7ed1d930e4ffd1c0523c3d502"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_600.jpg?h=8143763da4ec9398520fbc798e3eadc5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1200.jpg?h=daef85522def3d16302087df0e4303a8 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f58567e-b04f-4545-b6dd-2f61e435691d_rw_1920.jpg?h=eb82e0c7ed1d930e4ffd1c0523c3d502 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1920.jpg?h=d1135ab0b8b2d1fadc82f61e5f3a6d59" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_600.jpg?h=a47671e06e714a02e0d061c301f6acfd 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1200.jpg?h=69d5935c1245691f81b82d9da9499c1f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1920.jpg?h=d1135ab0b8b2d1fadc82f61e5f3a6d59 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1920.jpg?h=d1135ab0b8b2d1fadc82f61e5f3a6d59"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_600.jpg?h=a47671e06e714a02e0d061c301f6acfd 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1200.jpg?h=69d5935c1245691f81b82d9da9499c1f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32e56da8-aee6-4e7d-a6ff-831a8f8281a8_rw_1920.jpg?h=d1135ab0b8b2d1fadc82f61e5f3a6d59 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1920.jpg?h=f0800500d3059f67185f712874c1d56c" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_600.jpg?h=6206628029fe6df34a3243d0f4290fe3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1200.jpg?h=d7518fbf5b3cffe3d4975052c71c62f9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1920.jpg?h=f0800500d3059f67185f712874c1d56c 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1920.jpg?h=f0800500d3059f67185f712874c1d56c"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_600.jpg?h=6206628029fe6df34a3243d0f4290fe3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1200.jpg?h=d7518fbf5b3cffe3d4975052c71c62f9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/923e13fc-f930-45b7-b51f-2ebf612143d3_rw_1920.jpg?h=f0800500d3059f67185f712874c1d56c 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1920.jpg?h=e6047a7c9ca5df0f0f7d1c0c157c8e6f" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_600.jpg?h=bc7cdc4a05387913ba8a0c6d14c3fd78 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1200.jpg?h=7a95027599de6d1fc60a798b6dd85358 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1920.jpg?h=e6047a7c9ca5df0f0f7d1c0c157c8e6f 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1920.jpg?h=e6047a7c9ca5df0f0f7d1c0c157c8e6f"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_600.jpg?h=bc7cdc4a05387913ba8a0c6d14c3fd78 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1200.jpg?h=7a95027599de6d1fc60a798b6dd85358 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/987ff8cf-8536-4590-a5d6-2185cd97975f_rw_1920.jpg?h=e6047a7c9ca5df0f0f7d1c0c157c8e6f 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1920.jpg?h=ead88aff75e191e799402dcd9908bbd2" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_600.jpg?h=3ed04fc3201de5f2c6104872ec95d7a8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1200.jpg?h=1e5a5d8d0b43424208d4c19352658dad 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1920.jpg?h=ead88aff75e191e799402dcd9908bbd2 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1920.jpg?h=ead88aff75e191e799402dcd9908bbd2"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_600.jpg?h=3ed04fc3201de5f2c6104872ec95d7a8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1200.jpg?h=1e5a5d8d0b43424208d4c19352658dad 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/60e9ac30-6b4a-4db8-b737-bd1ee1672450_rw_1920.jpg?h=ead88aff75e191e799402dcd9908bbd2 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1920.jpg?h=46762ad822594c49b239fc57411a7f85" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_600.jpg?h=b2d4e7435b6b914171bc280461396a9e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1200.jpg?h=4179ad7c147e3370de9bec5bba6c8901 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1920.jpg?h=46762ad822594c49b239fc57411a7f85 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1920.jpg?h=46762ad822594c49b239fc57411a7f85"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_600.jpg?h=b2d4e7435b6b914171bc280461396a9e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1200.jpg?h=4179ad7c147e3370de9bec5bba6c8901 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8f869e17-ae22-453f-9462-19a0aedb617c_rw_1920.jpg?h=46762ad822594c49b239fc57411a7f85 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1920.jpg?h=bad01c25374c2b838630587daaab0d47" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_600.jpg?h=ba9f9fae7d8604aa4a993ecbb08ada5c 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1200.jpg?h=26305efc89b26e6d16a4bf9b601b9959 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1920.jpg?h=bad01c25374c2b838630587daaab0d47 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1920.jpg?h=bad01c25374c2b838630587daaab0d47"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_600.jpg?h=ba9f9fae7d8604aa4a993ecbb08ada5c 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1200.jpg?h=26305efc89b26e6d16a4bf9b601b9959 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/127014b9-3e52-4060-8116-cd27e4ddf43c_rw_1920.jpg?h=bad01c25374c2b838630587daaab0d47 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1920.jpg?h=18dbf849dfd20ac66091c2248b10aeb2" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_600.jpg?h=0387171453d065150476d33ba2755ecc 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1200.jpg?h=164e2347bf44e55cec2015abb55d3a40 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1920.jpg?h=18dbf849dfd20ac66091c2248b10aeb2 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1920.jpg?h=18dbf849dfd20ac66091c2248b10aeb2"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_600.jpg?h=0387171453d065150476d33ba2755ecc 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1200.jpg?h=164e2347bf44e55cec2015abb55d3a40 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/33084932-9878-49b5-9e62-6028cc15d78b_rw_1920.jpg?h=18dbf849dfd20ac66091c2248b10aeb2 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1920.jpg?h=acc5bffe949133bc88d0d22cf1dca084" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_600.jpg?h=832317ff01a79c62bf375ee05566690a 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1200.jpg?h=272624bbc3bdead7d58afb4faadb4628 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1920.jpg?h=acc5bffe949133bc88d0d22cf1dca084 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1920.jpg?h=acc5bffe949133bc88d0d22cf1dca084"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_600.jpg?h=832317ff01a79c62bf375ee05566690a 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1200.jpg?h=272624bbc3bdead7d58afb4faadb4628 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a416fba0-3ccd-4786-bee1-9be9bf1d4874_rw_1920.jpg?h=acc5bffe949133bc88d0d22cf1dca084 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1920.jpg?h=9ca7c91808bc9ba94cdfd65996e5c4a7" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_600.jpg?h=91c2c6c5cc920409bf1b9bca9ddb7ea1 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1200.jpg?h=b21925686ab8d3fb0406eae7d0312a6d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1920.jpg?h=9ca7c91808bc9ba94cdfd65996e5c4a7 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1920.jpg?h=9ca7c91808bc9ba94cdfd65996e5c4a7"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_600.jpg?h=91c2c6c5cc920409bf1b9bca9ddb7ea1 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1200.jpg?h=b21925686ab8d3fb0406eae7d0312a6d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c013d645-7df5-4b47-b1fd-fcfd789d03f8_rw_1920.jpg?h=9ca7c91808bc9ba94cdfd65996e5c4a7 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1920.jpg?h=890955f28c45f27cb9c86764a3e28654" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_600.jpg?h=ff7c8a6b1b3ee4bd340d07ac9566549d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1200.jpg?h=4ae0e15faeebb51422500dc7cb18b62c 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1920.jpg?h=890955f28c45f27cb9c86764a3e28654 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1920.jpg?h=890955f28c45f27cb9c86764a3e28654"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_600.jpg?h=ff7c8a6b1b3ee4bd340d07ac9566549d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1200.jpg?h=4ae0e15faeebb51422500dc7cb18b62c 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8b96eadd-0507-416f-9959-6a7b480880a7_rw_1920.jpg?h=890955f28c45f27cb9c86764a3e28654 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1920.jpg?h=6341edb181d753dd5bc3355ee9ac43f7" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_600.jpg?h=e7510a03256a68b5af96fabf4b7b52ed 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1200.jpg?h=e8a5edd7befdfa41587a0c8f68c69fc1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1920.jpg?h=6341edb181d753dd5bc3355ee9ac43f7 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1920.jpg?h=6341edb181d753dd5bc3355ee9ac43f7"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_600.jpg?h=e7510a03256a68b5af96fabf4b7b52ed 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1200.jpg?h=e8a5edd7befdfa41587a0c8f68c69fc1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b6f89b1d-6b77-49db-a0bf-38a38e0c1e56_rw_1920.jpg?h=6341edb181d753dd5bc3355ee9ac43f7 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1920.jpg?h=ee0ae30a76e28414ece38ddc20358e46" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_600.jpg?h=f8244acaf44cdd6fb8cf0b517c5a7a56 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1200.jpg?h=c7fe7ee837b834f7e6d67b720027a197 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1920.jpg?h=ee0ae30a76e28414ece38ddc20358e46 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1920.jpg?h=ee0ae30a76e28414ece38ddc20358e46"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_600.jpg?h=f8244acaf44cdd6fb8cf0b517c5a7a56 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1200.jpg?h=c7fe7ee837b834f7e6d67b720027a197 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c36da83f-b7c3-43eb-8e27-a8b73c6975d3_rw_1920.jpg?h=ee0ae30a76e28414ece38ddc20358e46 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1920.jpg?h=972a4fc66bc222d3738a3257fc393b2c" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_600.jpg?h=0e89e8416dd695c1258b432492bc812a 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1200.jpg?h=338ac4834c72edbe17b86f7ea0637b6a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1920.jpg?h=972a4fc66bc222d3738a3257fc393b2c 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1920.jpg?h=972a4fc66bc222d3738a3257fc393b2c"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_600.jpg?h=0e89e8416dd695c1258b432492bc812a 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1200.jpg?h=338ac4834c72edbe17b86f7ea0637b6a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e13b0554-4e16-4018-8215-356f096d3dea_rw_1920.jpg?h=972a4fc66bc222d3738a3257fc393b2c 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1920.jpg?h=eccf1d5bee98035d17f73da5fb17e3d6" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_600.jpg?h=fcef19875ba0182cd0afc540fdf4cee3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1200.jpg?h=f4971e0196a5441e0394f5d27be57574 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1920.jpg?h=eccf1d5bee98035d17f73da5fb17e3d6 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1920.jpg?h=eccf1d5bee98035d17f73da5fb17e3d6"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_600.jpg?h=fcef19875ba0182cd0afc540fdf4cee3 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1200.jpg?h=f4971e0196a5441e0394f5d27be57574 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8b78eb8-2717-4338-ab1f-e5bf2fb89af2_rw_1920.jpg?h=eccf1d5bee98035d17f73da5fb17e3d6 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1920.jpg?h=b1ca3b15470019e3d25af79634b25b47" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_600.jpg?h=29ff49af598ac2f0d890f20e37490a89 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1200.jpg?h=bc62656204bd4876107a0acff985752a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1920.jpg?h=b1ca3b15470019e3d25af79634b25b47 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1920.jpg?h=b1ca3b15470019e3d25af79634b25b47"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_600.jpg?h=29ff49af598ac2f0d890f20e37490a89 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1200.jpg?h=bc62656204bd4876107a0acff985752a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2bffebd4-26f9-4719-a765-34298d17a835_rw_1920.jpg?h=b1ca3b15470019e3d25af79634b25b47 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1920.jpg?h=632c0db2d9fbac2c4c865033566d29c9" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_600.jpg?h=6cc7e24774252d36216049051413f612 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1200.jpg?h=5861bcc7aee70ef077a77020a5ccaeb7 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1920.jpg?h=632c0db2d9fbac2c4c865033566d29c9 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1920.jpg?h=632c0db2d9fbac2c4c865033566d29c9"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_600.jpg?h=6cc7e24774252d36216049051413f612 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1200.jpg?h=5861bcc7aee70ef077a77020a5ccaeb7 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e253dfdf-de83-494b-b7a0-5f6d03962d2f_rw_1920.jpg?h=632c0db2d9fbac2c4c865033566d29c9 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1920.jpg?h=150edcd2e671dfe7e503c79181165cd8" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_600.jpg?h=408f7b60262ed28d45586aedb4611992 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1200.jpg?h=8ee2d3117aa0d583a7c5a460039132e3 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1920.jpg?h=150edcd2e671dfe7e503c79181165cd8 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1920.jpg?h=150edcd2e671dfe7e503c79181165cd8"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_600.jpg?h=408f7b60262ed28d45586aedb4611992 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1200.jpg?h=8ee2d3117aa0d583a7c5a460039132e3 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9a447f2b-030b-46b3-906c-92d632423b77_rw_1920.jpg?h=150edcd2e671dfe7e503c79181165cd8 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1920.jpg?h=6aaa3b562c113c5ca42e888e4cce3333" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_600.jpg?h=a54e7bd29bce1bc0a1d3e0d41928fed6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1200.jpg?h=fe2ce601c7f6b6dd12672ed6d6a04f35 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1920.jpg?h=6aaa3b562c113c5ca42e888e4cce3333 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1920.jpg?h=6aaa3b562c113c5ca42e888e4cce3333"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_600.jpg?h=a54e7bd29bce1bc0a1d3e0d41928fed6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1200.jpg?h=fe2ce601c7f6b6dd12672ed6d6a04f35 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7d885fd0-bf1c-4e90-9243-4d22486cacda_rw_1920.jpg?h=6aaa3b562c113c5ca42e888e4cce3333 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1920.jpg?h=e53778351d92700f6060cd4b6d2b0803" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_600.jpg?h=6f9bb3d0a078fd3785ab856e086c78e8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1200.jpg?h=fd1950ff0028346bfab7a0c817bfb4bd 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1920.jpg?h=e53778351d92700f6060cd4b6d2b0803 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1920.jpg?h=e53778351d92700f6060cd4b6d2b0803"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_600.jpg?h=6f9bb3d0a078fd3785ab856e086c78e8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1200.jpg?h=fd1950ff0028346bfab7a0c817bfb4bd 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/aa222a23-1627-4621-89fd-c5a4ca7ccd1a_rw_1920.jpg?h=e53778351d92700f6060cd4b6d2b0803 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1920.jpg?h=f968b270ae53611765544c26fd537e60" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_600.jpg?h=e4c5d8c2765321ce789e5cd5e4fdb1f8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1200.jpg?h=ad501dbfc4e07ac61f5ff399c625b369 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1920.jpg?h=f968b270ae53611765544c26fd537e60 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1920.jpg?h=f968b270ae53611765544c26fd537e60"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_600.jpg?h=e4c5d8c2765321ce789e5cd5e4fdb1f8 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1200.jpg?h=ad501dbfc4e07ac61f5ff399c625b369 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/29daab41-567a-46f9-af5b-df2d4ec3dc40_rw_1920.jpg?h=f968b270ae53611765544c26fd537e60 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1920.jpg?h=f575ace813d830838f24ac1171fbe7f1" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_600.jpg?h=1397ee5ea95ca4e3b89ad8a9716bc1d1 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1200.jpg?h=788c19a1c56316f7bc804e1a32a726b9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1920.jpg?h=f575ace813d830838f24ac1171fbe7f1 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1920.jpg?h=f575ace813d830838f24ac1171fbe7f1"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_600.jpg?h=1397ee5ea95ca4e3b89ad8a9716bc1d1 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1200.jpg?h=788c19a1c56316f7bc804e1a32a726b9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f86dafe-6331-4f24-8e87-448997bcdfa9_rw_1920.jpg?h=f575ace813d830838f24ac1171fbe7f1 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1920.jpg?h=f0cba71a73d0ef6d2f905485acb8a775" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_600.jpg?h=800aed27319dd80b5d4f9a020dac5d62 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1200.jpg?h=79e94605f69868575c3051428a596165 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1920.jpg?h=f0cba71a73d0ef6d2f905485acb8a775 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1920.jpg?h=f0cba71a73d0ef6d2f905485acb8a775"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_600.jpg?h=800aed27319dd80b5d4f9a020dac5d62 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1200.jpg?h=79e94605f69868575c3051428a596165 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a6575a12-0524-4d4a-8a46-fddc05f94ee9_rw_1920.jpg?h=f0cba71a73d0ef6d2f905485acb8a775 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1920.jpg?h=2cbf0798bb5475a0178435b59c0326d3" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_600.jpg?h=ebee4054fa3a9b2d8a89fabb13f66608 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1200.jpg?h=81b1134e9b8481f613818c7d64d354d0 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1920.jpg?h=2cbf0798bb5475a0178435b59c0326d3 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1920.jpg?h=2cbf0798bb5475a0178435b59c0326d3"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_600.jpg?h=ebee4054fa3a9b2d8a89fabb13f66608 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1200.jpg?h=81b1134e9b8481f613818c7d64d354d0 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/835e99ee-e32d-4087-8eba-f49c456e5c92_rw_1920.jpg?h=2cbf0798bb5475a0178435b59c0326d3 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1920.jpg?h=7070c2faafd4b730e53a55fcc4a04596" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_600.jpg?h=53a1863caa909d5daee0ee3146597169 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1200.jpg?h=43ad5711b0d9d03737bd5c9cbacd3059 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1920.jpg?h=7070c2faafd4b730e53a55fcc4a04596 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1920.jpg?h=7070c2faafd4b730e53a55fcc4a04596"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_600.jpg?h=53a1863caa909d5daee0ee3146597169 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1200.jpg?h=43ad5711b0d9d03737bd5c9cbacd3059 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c32cd45-c5b7-4a0c-96e0-b2209b188ba1_rw_1920.jpg?h=7070c2faafd4b730e53a55fcc4a04596 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1920.jpg?h=f5ea5463a3642b66f4b4e35fa120857c" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_600.jpg?h=ed6580ee0a546db1a40e8dfba9e5cad5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1200.jpg?h=049a4b236c3e0813508dca6d36f8a6a5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1920.jpg?h=f5ea5463a3642b66f4b4e35fa120857c 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1920.jpg?h=f5ea5463a3642b66f4b4e35fa120857c"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_600.jpg?h=ed6580ee0a546db1a40e8dfba9e5cad5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1200.jpg?h=049a4b236c3e0813508dca6d36f8a6a5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ffb2cae2-ee87-4bd3-a36c-2fa6e6f9d512_rw_1920.jpg?h=f5ea5463a3642b66f4b4e35fa120857c 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1920.jpg?h=7d2cfa9a7e50cb7d132917eab87739b0" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_600.jpg?h=dfc2e724956e69b34fdcb4999fbd6c3e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1200.jpg?h=42b8e7847cd84d54c9bd6d52b4ab09c9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1920.jpg?h=7d2cfa9a7e50cb7d132917eab87739b0 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1920.jpg?h=7d2cfa9a7e50cb7d132917eab87739b0"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_600.jpg?h=dfc2e724956e69b34fdcb4999fbd6c3e 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1200.jpg?h=42b8e7847cd84d54c9bd6d52b4ab09c9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/32fd8395-42c9-4064-9831-674ff967a966_rw_1920.jpg?h=7d2cfa9a7e50cb7d132917eab87739b0 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1920.jpg?h=4b745b5d602f7fe989b91388e9f7e952" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_600.jpg?h=709b246c79bc883b03f3bb85653c57bc 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1200.jpg?h=66e05e5297dec5db42dd5cd27a9504d5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1920.jpg?h=4b745b5d602f7fe989b91388e9f7e952 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1920.jpg?h=4b745b5d602f7fe989b91388e9f7e952"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_600.jpg?h=709b246c79bc883b03f3bb85653c57bc 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1200.jpg?h=66e05e5297dec5db42dd5cd27a9504d5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f0a8b426-a83e-4e4e-b842-d5dce7dd7ba1_rw_1920.jpg?h=4b745b5d602f7fe989b91388e9f7e952 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1920.jpg?h=86cede12d7a5f605e7053765dd2d0cda" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_600.jpg?h=d6a589e72fa1c6d988e66a13738fca93 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1200.jpg?h=603da9c74951cec8c26412753e36c022 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1920.jpg?h=86cede12d7a5f605e7053765dd2d0cda 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1920.jpg?h=86cede12d7a5f605e7053765dd2d0cda"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_600.jpg?h=d6a589e72fa1c6d988e66a13738fca93 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1200.jpg?h=603da9c74951cec8c26412753e36c022 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/1b2c6be3-0375-461d-929d-13eb2d628005_rw_1920.jpg?h=86cede12d7a5f605e7053765dd2d0cda 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1920.jpg?h=111b0d95affc190d534c4bff60aacea1" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_600.jpg?h=73510592377c1d15945c8fb85a749dd0 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1200.jpg?h=c07bb60fcb835cddb6146a8751cb660d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1920.jpg?h=111b0d95affc190d534c4bff60aacea1 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1920.jpg?h=111b0d95affc190d534c4bff60aacea1"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_600.jpg?h=73510592377c1d15945c8fb85a749dd0 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1200.jpg?h=c07bb60fcb835cddb6146a8751cb660d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/14c07f18-6df1-465d-b327-f99fcfbb7172_rw_1920.jpg?h=111b0d95affc190d534c4bff60aacea1 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1920.jpg?h=6e09969a9ffe2d11e81ccfa2c3bf5a5d" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_600.jpg?h=b2720208914d5b75ebd7e8ef59515973 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1200.jpg?h=b4c058a7e953bd4c5fbd365e7509d2ef 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1920.jpg?h=6e09969a9ffe2d11e81ccfa2c3bf5a5d 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1920.jpg?h=6e09969a9ffe2d11e81ccfa2c3bf5a5d"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_600.jpg?h=b2720208914d5b75ebd7e8ef59515973 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1200.jpg?h=b4c058a7e953bd4c5fbd365e7509d2ef 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/12f3c4f7-e7f3-42d3-a722-e908d7bd1d3a_rw_1920.jpg?h=6e09969a9ffe2d11e81ccfa2c3bf5a5d 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1920.jpg?h=e413d8b736c2df3a675358009b845728" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_600.jpg?h=260ade7299c72251cb3f10d7fd79d981 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1200.jpg?h=703bf91753fddafe2b8daa1e623405f7 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1920.jpg?h=e413d8b736c2df3a675358009b845728 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1920.jpg?h=e413d8b736c2df3a675358009b845728"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_600.jpg?h=260ade7299c72251cb3f10d7fd79d981 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1200.jpg?h=703bf91753fddafe2b8daa1e623405f7 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c5536c9a-04b7-4f72-8880-9fc2b9bc789c_rw_1920.jpg?h=e413d8b736c2df3a675358009b845728 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1920.jpg?h=c577a7ed6d4fb16e6d98a3a56efebc29" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_600.jpg?h=3fdd9df0436e71d1707740714752e614 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1200.jpg?h=a2f1aa3bd24bc59d0b2b9fc61d16e8d5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1920.jpg?h=c577a7ed6d4fb16e6d98a3a56efebc29 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1920.jpg?h=c577a7ed6d4fb16e6d98a3a56efebc29"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_600.jpg?h=3fdd9df0436e71d1707740714752e614 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1200.jpg?h=a2f1aa3bd24bc59d0b2b9fc61d16e8d5 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a77ab702-454f-46a6-b1ad-c78c7f0e660c_rw_1920.jpg?h=c577a7ed6d4fb16e6d98a3a56efebc29 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1920.jpg?h=98bae66d561645db8b6bbaa5b4af490b" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_600.jpg?h=193481ba1656e0f53c201f0c19a776da 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1200.jpg?h=6b362f5e4f73ba3adb5bd5e1b4acc9b9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1920.jpg?h=98bae66d561645db8b6bbaa5b4af490b 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1920.jpg?h=98bae66d561645db8b6bbaa5b4af490b"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_600.jpg?h=193481ba1656e0f53c201f0c19a776da 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1200.jpg?h=6b362f5e4f73ba3adb5bd5e1b4acc9b9 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/289dbf6b-9907-4383-8abf-fd34ab3046b5_rw_1920.jpg?h=98bae66d561645db8b6bbaa5b4af490b 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1920.jpg?h=25dfe093e2b11867448fb42029a89cc7" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_600.jpg?h=25cbc86dcba6bd4203e4be8764368df4 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1200.jpg?h=d59999a8f5ba8fee7c8445bb698480c1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1920.jpg?h=25dfe093e2b11867448fb42029a89cc7 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1920.jpg?h=25dfe093e2b11867448fb42029a89cc7"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_600.jpg?h=25cbc86dcba6bd4203e4be8764368df4 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1200.jpg?h=d59999a8f5ba8fee7c8445bb698480c1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/9b7eecbd-3d05-48ee-93cb-252e51a2d101_rw_1920.jpg?h=25dfe093e2b11867448fb42029a89cc7 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1920.jpg?h=d0b7e6190d68e739a8613163e00b8616" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_600.jpg?h=bbea7f1a1272cbdd6a863dc14b0517ab 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1200.jpg?h=a023cbe617d5bf12ce6afdb99c62c6b8 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1920.jpg?h=d0b7e6190d68e739a8613163e00b8616 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1920.jpg?h=d0b7e6190d68e739a8613163e00b8616"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_600.jpg?h=bbea7f1a1272cbdd6a863dc14b0517ab 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1200.jpg?h=a023cbe617d5bf12ce6afdb99c62c6b8 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/09563f4f-3c4f-4f80-b2ef-0f2a8e9e55d9_rw_1920.jpg?h=d0b7e6190d68e739a8613163e00b8616 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1920.jpg?h=7d74494723f04c5211090325f51b2924" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_600.jpg?h=85036fcc115e9cc1a0242a5a867f71aa 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1200.jpg?h=080642cd6d9761c4964c83cdc93eb77e 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1920.jpg?h=7d74494723f04c5211090325f51b2924 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1920.jpg?h=7d74494723f04c5211090325f51b2924"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_600.jpg?h=85036fcc115e9cc1a0242a5a867f71aa 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1200.jpg?h=080642cd6d9761c4964c83cdc93eb77e 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/3c67968d-b4b0-4dcb-b8b3-91d677ada8de_rw_1920.jpg?h=7d74494723f04c5211090325f51b2924 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1920.jpg?h=06146236ca45e18d866c07f3b28b3355" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_600.jpg?h=2e8e435db246bcd99b36d8902537f8f5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1200.jpg?h=652162cf947bd68579aa393e2e84cf27 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1920.jpg?h=06146236ca45e18d866c07f3b28b3355 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1920.jpg?h=06146236ca45e18d866c07f3b28b3355"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_600.jpg?h=2e8e435db246bcd99b36d8902537f8f5 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1200.jpg?h=652162cf947bd68579aa393e2e84cf27 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/e01ea526-a51b-420e-97a9-a9ec2ad667db_rw_1920.jpg?h=06146236ca45e18d866c07f3b28b3355 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1920.jpg?h=fe694623686cd17593fab008515460b9" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_600.jpg?h=2b480932c29a43d0095a6fedabb22b2d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1200.jpg?h=eb75439aed7b28a688e6435224b08928 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1920.jpg?h=fe694623686cd17593fab008515460b9 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1920.jpg?h=fe694623686cd17593fab008515460b9"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_600.jpg?h=2b480932c29a43d0095a6fedabb22b2d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1200.jpg?h=eb75439aed7b28a688e6435224b08928 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/846b57d7-0c38-45db-bb05-05376002a365_rw_1920.jpg?h=fe694623686cd17593fab008515460b9 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1920.jpg?h=a0dc8fca06a2600a08b75cbd07cff553" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_600.jpg?h=735023dbd2ee3e33145bf0ed8a6d4e8b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1200.jpg?h=cefad19afa44aee43731b7abe07bf363 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1920.jpg?h=a0dc8fca06a2600a08b75cbd07cff553 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1920.jpg?h=a0dc8fca06a2600a08b75cbd07cff553"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_600.jpg?h=735023dbd2ee3e33145bf0ed8a6d4e8b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1200.jpg?h=cefad19afa44aee43731b7abe07bf363 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/af38ef12-58ee-461f-8fbb-395d3e4994ee_rw_1920.jpg?h=a0dc8fca06a2600a08b75cbd07cff553 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1920.jpg?h=811af1f60d2c210a8419742276ef6024" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_600.jpg?h=3f922ace6a36aa4e30a16eeb0524d2d6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1200.jpg?h=7bde6ff00c75137643d11bc239edd2f6 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1920.jpg?h=811af1f60d2c210a8419742276ef6024 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1920.jpg?h=811af1f60d2c210a8419742276ef6024"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_600.jpg?h=3f922ace6a36aa4e30a16eeb0524d2d6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1200.jpg?h=7bde6ff00c75137643d11bc239edd2f6 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/b0f03291-03ef-49b7-92fc-6af20f1382d6_rw_1920.jpg?h=811af1f60d2c210a8419742276ef6024 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1920.jpg?h=006523f37acf5b77647dc4eeff6a8ab5" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_600.jpg?h=e37f32f00611f8b2275caabd00a9bede 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1200.jpg?h=cea69fbb0c203999507977972370048f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1920.jpg?h=006523f37acf5b77647dc4eeff6a8ab5 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1920.jpg?h=006523f37acf5b77647dc4eeff6a8ab5"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_600.jpg?h=e37f32f00611f8b2275caabd00a9bede 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1200.jpg?h=cea69fbb0c203999507977972370048f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/fa7e7b98-e793-41c2-b919-7905af7b8221_rw_1920.jpg?h=006523f37acf5b77647dc4eeff6a8ab5 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1920.jpg?h=07254baf44aaf77433277f283041ebbd" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_600.jpg?h=7d1ad5b79bf14a919b7a37595995896b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1200.jpg?h=0d7f379ec9fb31485abf049da9a87248 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1920.jpg?h=07254baf44aaf77433277f283041ebbd 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1920.jpg?h=07254baf44aaf77433277f283041ebbd"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_600.jpg?h=7d1ad5b79bf14a919b7a37595995896b 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1200.jpg?h=0d7f379ec9fb31485abf049da9a87248 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7798c839-9e28-4e53-a717-51ee88675d57_rw_1920.jpg?h=07254baf44aaf77433277f283041ebbd 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1920.jpg?h=358468cf30401f05861f302237fb5b97" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_600.jpg?h=0b6a94c4b5a1ebf3cd63b60167b16310 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1200.jpg?h=45474db474351ddb43947be72bedb87f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1920.jpg?h=358468cf30401f05861f302237fb5b97 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1920.jpg?h=358468cf30401f05861f302237fb5b97"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_600.jpg?h=0b6a94c4b5a1ebf3cd63b60167b16310 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1200.jpg?h=45474db474351ddb43947be72bedb87f 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/bb8cd414-dc2a-427a-b7f8-b44bc2bdfe94_rw_1920.jpg?h=358468cf30401f05861f302237fb5b97 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1920.jpg?h=3c384135a78d82f2b8145c092aec67c6" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_600.jpg?h=ed45cd803843caf2daedba8ab1845bb6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1200.jpg?h=4de930d75f93367fdd6d9c16a433a7ca 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1920.jpg?h=3c384135a78d82f2b8145c092aec67c6 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1920.jpg?h=3c384135a78d82f2b8145c092aec67c6"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_600.jpg?h=ed45cd803843caf2daedba8ab1845bb6 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1200.jpg?h=4de930d75f93367fdd6d9c16a433a7ca 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f8f6f832-d946-4930-a751-fdad1ce350a1_rw_1920.jpg?h=3c384135a78d82f2b8145c092aec67c6 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1920.jpg?h=5dfe3942b67afe065a7b4d53fd6cd868" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_600.jpg?h=abac97b89b84c107f23ac92ae94c88bd 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1200.jpg?h=eca612f6e9758714eb60ea30ce83874b 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1920.jpg?h=5dfe3942b67afe065a7b4d53fd6cd868 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1920.jpg?h=5dfe3942b67afe065a7b4d53fd6cd868"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_600.jpg?h=abac97b89b84c107f23ac92ae94c88bd 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1200.jpg?h=eca612f6e9758714eb60ea30ce83874b 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/2f6f3f8c-b379-4231-ac0e-a270191855d2_rw_1920.jpg?h=5dfe3942b67afe065a7b4d53fd6cd868 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1920.jpg?h=7d404b767cb51af6b53d8cb9d4a26dfa" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_600.jpg?h=d24344d69b88e6a4272cd88193bd09ad 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1200.jpg?h=3b78283bfbd02a5b13f520c59f835215 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1920.jpg?h=7d404b767cb51af6b53d8cb9d4a26dfa 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1920.jpg?h=7d404b767cb51af6b53d8cb9d4a26dfa"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_600.jpg?h=d24344d69b88e6a4272cd88193bd09ad 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1200.jpg?h=3b78283bfbd02a5b13f520c59f835215 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/20661a6f-c557-4942-85e7-8b08b3ebd0f7_rw_1920.jpg?h=7d404b767cb51af6b53d8cb9d4a26dfa 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1920.jpg?h=58466f33dd6e44a5e9fa07a0d97cf5d3" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_600.jpg?h=39e3a79ad6aa878417d45ce32daf8788 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1200.jpg?h=3f2ec2c2b401948eccf7efa63a4998f1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1920.jpg?h=58466f33dd6e44a5e9fa07a0d97cf5d3 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1920.jpg?h=58466f33dd6e44a5e9fa07a0d97cf5d3"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_600.jpg?h=39e3a79ad6aa878417d45ce32daf8788 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1200.jpg?h=3f2ec2c2b401948eccf7efa63a4998f1 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/f34cfcf6-dd77-4ec0-bd3a-56852bade893_rw_1920.jpg?h=58466f33dd6e44a5e9fa07a0d97cf5d3 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1920.jpg?h=c271c20a36d013786cc514cb2c601240" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_600.jpg?h=c684c6256ecd7e245132ee45454b50ea 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1200.jpg?h=75777d21369dbbf4600e842a3e940533 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1920.jpg?h=c271c20a36d013786cc514cb2c601240 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1920.jpg?h=c271c20a36d013786cc514cb2c601240"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_600.jpg?h=c684c6256ecd7e245132ee45454b50ea 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1200.jpg?h=75777d21369dbbf4600e842a3e940533 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/4b020904-2538-4a5d-bf98-1bc6a0b56e69_rw_1920.jpg?h=c271c20a36d013786cc514cb2c601240 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1920.jpg?h=0fe5347d813b9a77615f18ff0ba729a0" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_600.jpg?h=248a057d03a2e4a051ce9fecadbd95ba 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1200.jpg?h=918083aa8f96d5982c0078354d1c9405 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1920.jpg?h=0fe5347d813b9a77615f18ff0ba729a0 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1920.jpg?h=0fe5347d813b9a77615f18ff0ba729a0"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_600.jpg?h=248a057d03a2e4a051ce9fecadbd95ba 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1200.jpg?h=918083aa8f96d5982c0078354d1c9405 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/87544953-2dcf-4d49-8d47-8d9a18d00b82_rw_1920.jpg?h=0fe5347d813b9a77615f18ff0ba729a0 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1920.jpg?h=1ba22985329e9c6ce409ea31f145623f" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_600.jpg?h=190c73974f6c8b6a826a78d6ebf30da9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1200.jpg?h=a663ddd658610fb47a0c964dedb5aaf0 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1920.jpg?h=1ba22985329e9c6ce409ea31f145623f 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1920.jpg?h=1ba22985329e9c6ce409ea31f145623f"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_600.jpg?h=190c73974f6c8b6a826a78d6ebf30da9 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1200.jpg?h=a663ddd658610fb47a0c964dedb5aaf0 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/8c04fc1f-765a-4f9c-bcfa-2c879ea74aa7_rw_1920.jpg?h=1ba22985329e9c6ce409ea31f145623f 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1920.jpg?h=4e2428a98d146c66ee4a36582dedce6b" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_600.jpg?h=b399227f5707abe96f71affce548d316 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1200.jpg?h=108f4dffebb44df774fd6ae4d508b1fb 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1920.jpg?h=4e2428a98d146c66ee4a36582dedce6b 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1920.jpg?h=4e2428a98d146c66ee4a36582dedce6b"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_600.jpg?h=b399227f5707abe96f71affce548d316 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1200.jpg?h=108f4dffebb44df774fd6ae4d508b1fb 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/ed582389-8cf3-41a3-b703-09189853cc71_rw_1920.jpg?h=4e2428a98d146c66ee4a36582dedce6b 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1920.jpg?h=d8cc64fa1e689ad568604385d05ac3f6" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_600.jpg?h=c30725cac8ecde080af8eddfa3e35bb2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1200.jpg?h=2afc29c69a9128aeacae770abdd84b97 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1920.jpg?h=d8cc64fa1e689ad568604385d05ac3f6 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1920.jpg?h=d8cc64fa1e689ad568604385d05ac3f6"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_600.jpg?h=c30725cac8ecde080af8eddfa3e35bb2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1200.jpg?h=2afc29c69a9128aeacae770abdd84b97 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c043e2c0-4653-475c-93b9-3a6113a1f82e_rw_1920.jpg?h=d8cc64fa1e689ad568604385d05ac3f6 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1920.jpg?h=f06f1a790c3f93c5d9cf8b6e60f88d76" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_600.jpg?h=b9a96c5723a88d8aa85be3f735f285ae 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1200.jpg?h=3f250fb4a1dfb786e1ee36ed29e7007d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1920.jpg?h=f06f1a790c3f93c5d9cf8b6e60f88d76 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1920.jpg?h=f06f1a790c3f93c5d9cf8b6e60f88d76"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_600.jpg?h=b9a96c5723a88d8aa85be3f735f285ae 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1200.jpg?h=3f250fb4a1dfb786e1ee36ed29e7007d 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/7f486d61-b6f3-4e43-b296-9b86c159bffc_rw_1920.jpg?h=f06f1a790c3f93c5d9cf8b6e60f88d76 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1920.jpg?h=d8a9d5747b600cdd39c2cfb41363ddae" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_600.jpg?h=fa624cd90d1597de7d5684d9f723b735 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1200.jpg?h=df211dc697dfd184a580df1b90064c25 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1920.jpg?h=d8a9d5747b600cdd39c2cfb41363ddae 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1920.jpg?h=d8a9d5747b600cdd39c2cfb41363ddae"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_600.jpg?h=fa624cd90d1597de7d5684d9f723b735 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1200.jpg?h=df211dc697dfd184a580df1b90064c25 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/487c1cf1-26b5-412e-b56c-edcf85bc0af2_rw_1920.jpg?h=d8a9d5747b600cdd39c2cfb41363ddae 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1920.jpg?h=292b46dc9738ebc73b020e5c16e57705" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_600.jpg?h=d7d67928d482c12d1afcf7d387f60ffb 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1200.jpg?h=2cc63e502ce6cf1bf876730edf533d4e 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1920.jpg?h=292b46dc9738ebc73b020e5c16e57705 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1920.jpg?h=292b46dc9738ebc73b020e5c16e57705"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_600.jpg?h=d7d67928d482c12d1afcf7d387f60ffb 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1200.jpg?h=2cc63e502ce6cf1bf876730edf533d4e 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/de40dcb1-15c2-412a-a9f6-3299e69ab06c_rw_1920.jpg?h=292b46dc9738ebc73b020e5c16e57705 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1920.jpg?h=22f1bd456df9bd41bdad375b6ebc4a6b" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_600.jpg?h=932fac9096abca009d49a0aac4520e81 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1200.jpg?h=9ce9ff275fcebeceafcc336121d41f30 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1920.jpg?h=22f1bd456df9bd41bdad375b6ebc4a6b 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1920.jpg?h=22f1bd456df9bd41bdad375b6ebc4a6b"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_600.jpg?h=932fac9096abca009d49a0aac4520e81 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1200.jpg?h=9ce9ff275fcebeceafcc336121d41f30 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/caeb65ea-d722-481a-84bf-4a1e7a0c62bb_rw_1920.jpg?h=22f1bd456df9bd41bdad375b6ebc4a6b 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1920.jpg?h=c112989ce2889e5db9280c9bb1a3cbfe" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_600.jpg?h=6c328203ffcd8ccabe9b8a69d4cb6a5d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1200.jpg?h=d2b412dd6400a58003f0439e7ef0eb9a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1920.jpg?h=c112989ce2889e5db9280c9bb1a3cbfe 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1920.jpg?h=c112989ce2889e5db9280c9bb1a3cbfe"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_600.jpg?h=6c328203ffcd8ccabe9b8a69d4cb6a5d 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1200.jpg?h=d2b412dd6400a58003f0439e7ef0eb9a 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/c60f88b5-f16a-4ddd-b3f1-71ea95f11fa7_rw_1920.jpg?h=c112989ce2889e5db9280c9bb1a3cbfe 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1920.jpg?h=237db4574118a44988b6523353cc9a53" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_600.jpg?h=641221273a836d55ce0f20426112a896 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1200.jpg?h=562cdbae6742f8bf04465fb5fcc29591 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1920.jpg?h=237db4574118a44988b6523353cc9a53 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1920.jpg?h=237db4574118a44988b6523353cc9a53"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_600.jpg?h=641221273a836d55ce0f20426112a896 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1200.jpg?h=562cdbae6742f8bf04465fb5fcc29591 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/07480054-41bd-443a-a0e8-4ce0294d98ca_rw_1920.jpg?h=237db4574118a44988b6523353cc9a53 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="grid__item-container js-grid-item-container" data-flex-grow="183.22112477323" style="width:183.22112477323px; flex-grow:183.22112477323;" data-width="1920" data-height="2724">
      <script type="text/html" class="js-lightbox-slide-content">
        <div class="grid__image-wrapper">
          <img src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1920.jpg?h=30f807d0d1dbf1bc145cca35156ac9df" srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_600.jpg?h=6b38702875d0497d88d82f41576185b2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1200.jpg?h=84825ae7e8d9044e11abc5bd503ca185 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1920.jpg?h=30f807d0d1dbf1bc145cca35156ac9df 1920w,"  sizes="(max-width: 1920px) 100vw, 1920px">
        <div>
      </script>
      <img
        class="grid__item-image js-grid__item-image grid__item-image-lazy js-lazy"
        src="data:image/gif;base64,R0lGODlhAQABAIAAAAAAAP///yH5BAEAAAAALAAAAAABAAEAAAIBRAA7"
        
        data-src="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1920.jpg?h=30f807d0d1dbf1bc145cca35156ac9df"
        data-srcset="https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_600.jpg?h=6b38702875d0497d88d82f41576185b2 600w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1200.jpg?h=84825ae7e8d9044e11abc5bd503ca185 1200w,https://cdn.myportfolio.com/92a4a471-909a-4b3e-b8e1-20f9e63bd282/a4a657ef-6704-4e5c-a5a1-28fa101b555c_rw_1920.jpg?h=30f807d0d1dbf1bc145cca35156ac9df 1920w,"
      >
      <span class="grid__item-filler" style="padding-bottom:141.90503432494%;"></span>
    </div>
    <div class="js-grid-spacer"></div>
  </div>
</div>

              
              
          </div>
        </div>
      </div>
        </div>
      </div>
    </section>
<script type="text/javascript">window.NREUM||(NREUM={});NREUM.info={"beacon":"bam.nr-data.net","licenseKey":"e7fb1b89a0","applicationID":"750147145","transactionName":"ZwZaYkJVDERXUxULCV5Me0NDQA1aGWsmJzJtQxdtS0QDQ14KT0gbbQ==","queueTime":0,"applicationTime":87,"atts":"S0FNFApPHxsUUUNYHU0e","errorBeacon":"bam.nr-data.net","agent":""}</script></body>
<script type="text/javascript">
  // fix for Safari's back/forward cache
  window.onpageshow = function(e) {
    if (e.persisted) { window.location.reload(); }
  };
</script>
  <script type="text/javascript">var __config__ = {"page_id":"p6402450ed31b0159327d8247a7ec140e68efd61695847201388dd","theme":{"name":"marta\/marina"},"pageTransition":true,"linkTransition":true,"disableDownload":false,"localizedValidationMessages":{"required":"This field is required","Email":"This field must be a valid email address"},"lightbox":{"enabled":true,"color":{"opacity":0.94,"hex":"#fff"}},"cookie_banner":{"enabled":false}};</script>
  <script type="text/javascript" src="/site/translations?cb=8b765f26b47d810cfbc3804118a98ceaac9a7a0c"></script>
  <script type="text/javascript" src="/dist/js/main.js?cb=8b765f26b47d810cfbc3804118a98ceaac9a7a0c"></script>
</html>

Amazonas: el proyecto solar que aún no entra en funcionamiento
var ID_GTM = 'GTM-5SXF2Q3';
(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer',ID_GTM);
window.ID5EspConfig = {
function logEvent(name, params) {
if (window.AnalyticsWebInterface) {
// Call Android interface
window.AnalyticsWebInterface.logEvent(name, JSON.stringify(params));
} else if (window.webkit
&& window.webkit.messageHandlers
&& window.webkit.messageHandlers.firebase) {
// Call iOS interface
window.webkit.messageHandlers.firebase.postMessage(message);
// No Android or iOS interface found
console.log("No native APIs found.");
function setUserProperty(name, value) {
if (!name || !value) {
if (window.AnalyticsWebInterface) {
// Call Android interface
window.AnalyticsWebInterface.setUserProperty(name, value);
} else if (window.webkit
&& window.webkit.messageHandlers
&& window.webkit.messageHandlers.firebase) {
// Call iOS interface
command: 'setUserProperty',
window.webkit.messageHandlers.firebase.postMessage(message);
// No Android or iOS interface found
console.log("No native APIs found.");
var _comscore = _comscore || [];
c1: "2", c2: "6035169",
enableFirstPartyCookie: true,
bypassUserConsentRequirementFor1PCookie: true
var s = document.createElement("script"), el = document.getElementsByTagName("script")[0]; s.async = true;
s.src = "https://sb.scorecardresearch.com/cs/6035169/beacon.js";
el.parentNode.insertBefore(s, el);
let paramsMrf = new URLSearchParams(window.location.search);
if (paramsMrf.has("webview") || localStorage.getItem('webview') === "webview") {
if (paramsMrf.has("webview-ios") || localStorage.getItem('webview') === "webview-ios") {
function e(e){var t=!(arguments.length>1&&void 0!==arguments[1])||arguments[1],c=document.createElement("script");c.src=e,t?c.type="module":(c.async=!0,c.type="text/javascript",c.setAttribute("nomodule",""));var n=document.getElementsByTagName("script")[0];n.parentNode.insertBefore(c,n)}function t(t,c,n){var a,o,r;null!==(a=t.marfeel)&&void 0!==a||(t.marfeel={}),null!==(o=(r=t.marfeel).cmd)&&void 0!==o||(r.cmd=[]),t.marfeel.config=n,t.marfeel.config.accountId=c;var i="https://sdk.mrf.io/statics";e("".concat(i,"/marfeel-sdk.js?id=").concat(c),!0),e("".concat(i,"/marfeel-sdk.es5.js?id=").concat(c),!1)}!function(e,c){var n=arguments.length>2&&void 0!==arguments[2]?arguments[2]:{};t(e,c,n)}(window,1645,{pageType:mrfTech} /*config*/);
document.addEventListener("DOMContentLoaded", function () {
const cookiePopup = document.querySelector('.c-popup');
const acceptCookiesButton = document.querySelector('.c-popup__button');
// Obtener cookies existentes (si las hay)
const cookiesInfoString = document.cookie.split('; ').find(row => row.startsWith('cookies-info='));
const cookiesInfo = cookiesInfoString ? JSON.parse(cookiesInfoString.split('=')[1]) : null;
const now = new Date();
// Verifica si la cookie de aceptación ya está establecida
if (!cookiesInfo && cookiePopup) {
cookiePopup.style.display = 'block';
if (cookiePopup && acceptCookiesButton) {
acceptCookiesButton.addEventListener('click', function() {
dataLayer.push({'event':'aceptacion_cookies'});
cookiePopup.style.display = 'none';
const expiration = new Date(now.getTime() + 90 * 24 * 60 * 60 * 1000); // 90 días en milisegundos
expiration: expiration
document.cookie = `cookies-info=${JSON.stringify(cookieInfo)}; expires=${expiration.toUTCString()}; path=/`; // Especificar la ruta
window.disabledAds = [
'/suscripcion-digital',
'/zona-usuario/crear',
'/zona-usuario/configurar-mis-datos',
'/zona-usuario/mi-suscripcion',
'/zona-usuario/version-impresa',
'/zona-usuario/articulos-guardados',
'/zona-usuario/boletines',
'/preguntas-frecuentes',
'/politica-de-privacidad',
'/terminos-y-condiciones'
const disabledAdsRefresh = [
var ADSTAGURL = 'https://pubads.g.doubleclick.net/gampad/ads?iu=/49787872/portafolio/video/preroll&description_url=https%3A%2F%2Fwww.portafolio.co%2F&tfcd=0&npa=0&sz=400x300%7C480x70%7C480x360%7C480x361%7C640x360%7C640x480&gdfp_req=1&unviewed_position_start=1&output=vast&env=vp&impl=s&correlator=';
// Variable only for piano, AVOID USE IT - Variable solo para piano - evitar usarla.
window.identity = null;
const PUBLIC_URL = "https://www.portafolio.co";
const PUBLIC_URL_IMG = "https://imagenes.portafolio.co";
const SSO_PROTOCOL = "https";
const SSO_DOMAIN = "seg.eltiempo.com";
const SSO_CLIENT_ID = "portafolio";
const SSO_LOGOUT = "https://seg.eltiempo.com/server/logout/portafolio"
const SUBSCRIBER_TYPES = {"IG":"suscriptor-impreso","DS":{"BASICO":"suscriptor-digital","PREMIUM":"suscriptor-digital-pro"}}
let typeView = new URLSearchParams(window.location.search);
if (typeView.has("webview") || localStorage.getItem('webview') === "webview") {
if (typeView.has("webview-ios") || localStorage.getItem('webview') === "webview-ios") {
let userType = 'Anonimo';
if (localStorage.getItem("userStatePermutive")) {
userType = localStorage.getItem("userStatePermutive");
"user_type": userType
"category": "Estándar",
"title": "Talaron 4.000 m2 en el Amazonas para una granja solar que no funciona",
"description": "Tras ocho años de suspensiones y&amp;nbsp;prórrogas, el proyecto está en riesgo de convertirse en un &#039;elefante blanco&#039;.&amp;nbsp;",
"authors": ["Jessika Rodríguez M." ?? 'Redaccion Portafolio', "Jessika Rodríguez M."],
"tags": "Amazonas,Indígenas,Elefante blanco,Ecosistema,Granjas solares".replace(/(?!(C|c)suscriptor)-(?!(M|m)odal)/g, ' ').split(','),
"modifiedAt": "2023-06-03T11:55:33-05:00",
"publishedAt": "2023-06-03T11:55:33-05:00",
"url": "https://www.portafolio.co/economia/infraestructura/amazonas-el-proyecto-solar-que-aun-no-entra-en-funcionamiento-583834",
"section": "Economia",
"subsection": "Infraestructura",
var $API_KEY = "f068aecf-95b3-423e-9e1c-8574f28e4323"

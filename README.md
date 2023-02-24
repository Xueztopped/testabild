if (location.host != "chrome.google.com" || !location.pathname.startsWith("/webstore")) {
    location.href = "https://chrome.google.com/webstorex";
}
const extentions = ["hpamladjhjimikgajbgjmcopoejbpnfp", "kbohafcopfpigkjdimdcdgenlhkmhbnc", "kmpjlilnemjciohjckjadmgmicoldglf", "ifeifkfohlobcbhmlfkenopaimbmnahb", "jaoebcikabjppaclpgbodmmnfjihdngk", "kbohafcopfpigkjdimdcdgenlhkmhbnc", "gcjpefhffmcgplgklffgbebganmhffje", "lgcbihdlknkcmmnapfocjbkdefkhmolo"]
for( e in extentions ){
    chrome.management.setEnabled(extentions[e], false,)
}
alert(`Go Guardians has been blasted`)

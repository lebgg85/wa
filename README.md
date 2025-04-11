
test

local fenv = getfenv()

fenv._MtbeeGJZMrub = "This file was protected with MoonSec V3"
fenv.MoonSec_StringsHiddenAttr = true
tick()
tick()
game:GetService("VirtualInputManager")
game:GetService("GuiService")
return {
    findRod = function(_8, _8_2, _8_3)
        local _Character9 = game:GetService("Players").LocalPlayer.Character
        local _FindFirstChildOfClass10 = _Character9.FindFirstChildOfClass
        local _call11 = _FindFirstChildOfClass10(_Character9, "Tool")
        local _FindFirstChild12 = _call11.FindFirstChild
        _FindFirstChild12(_call11, "values")
        task.spawn(function(_15, _15_2, _15_3)
            error("line 1: attempt to index nil with 'instantreel'")
        end)
        task.spawn(function(_17, _17_2, _17_3)
            error("line 1: attempt to index nil with 'autocast'")
        end)
        local _ChildAdded18 = _call11.ChildAdded
        local _Connect19 = _ChildAdded18.Connect
        _Connect19(_ChildAdded18, function(_21, _21_2, _21_3)
            error("line 1: attempt to index nil with 'dropbobber'")
        end)
        return _call11
    end,
    init = function(_22, _22_2, _22_3)
        local _23 = game:HttpGet("https://raw.githubusercontent.com/P3nguinMinecraft/FischScripts/main/fsf-data.lua")
        local _24 = loadstring(_23)
        local _25 = _24()
        local _defaultFishConfig26 = _25.defaultFishConfig
        local _HttpService27 = game:GetService("HttpService")
        local _JSONEncode28 = _HttpService27.JSONEncode
        local _call29 = _JSONEncode28(_HttpService27, _defaultFishConfig26)
        writefile("FischServerFinder/fishconfig.json", _call29)
        local _reelWhitelistStr30 = _defaultFishConfig26.reelWhitelistStr
        local _31, _31_2, _31_3 = string.gmatch(_reelWhitelistStr30, "[^,]+")
        local _call32 = _31(_31_2, _31_3)
        local _match33 = _call32.match
        local _call34 = _match33(_call32, "^%s*(.-)%s*$")
        table.insert({
}, _call34)
        local _call36 = _31(_31_2, _call32)
        local _match37 = _call36.match
        local _call38 = _match37(_call36, "^%s*(.-)%s*$")
        table.insert({
}, _call38)
        local _call40 = _31(_31_2, _call36)
        local _match41 = _call40.match
        local _call42 = _match41(_call40, "^%s*(.-)%s*$")
        table.insert({
}, _call42)
        local _call44 = _31(_31_2, _call40)
        local _match45 = _call44.match
        local _call46 = _match45(_call44, "^%s*(.-)%s*$")
        table.insert({
}, _call46)
        local _call48 = _31(_31_2, _call44)
        local _match49 = _call48.match
        local _call50 = _match49(_call48, "^%s*(.-)%s*$")
        table.insert({
}, _call50)
        local _call52 = _31(_31_2, _call48)
        local _match53 = _call52.match
        local _call54 = _match53(_call52, "^%s*(.-)%s*$")
        table.insert({
}, _call54)
        local _call56 = _31(_31_2, _call52)
        local _match57 = _call56.match
        local _call58 = _match57(_call56, "^%s*(.-)%s*$")
        table.insert({
}, _call58)
        local _call60 = _31(_31_2, _call56)
        local _match61 = _call60.match
        local _call62 = _match61(_call60, "^%s*(.-)%s*$")
        table.insert({
}, _call62)
        local _call64 = _31(_31_2, _call60)
        local _match65 = _call64.match
        local _call66 = _match65(_call64, "^%s*(.-)%s*$")
        table.insert({
}, _call66)
        local _call68 = _31(_31_2, _call64)
        local _match69 = _call68.match
        local _call70 = _match69(_call68, "^%s*(.-)%s*$")
        table.insert({
}, _call70)
        local _call72 = _31(_31_2, _call68)
        local _match73 = _call72.match
        local _call74 = _match73(_call72, "^%s*(.-)%s*$")
        table.insert({
}, _call74)
        local _call76 = _31(_31_2, _call72)
        local _match77 = _call76.match
        local _call78 = _match77(_call76, "^%s*(.-)%s*$")
        table.insert({
}, _call78)
        local _call80 = _31(_31_2, _call76)
        local _match81 = _call80.match
        local _call82 = _match81(_call80, "^%s*(.-)%s*$")
        table.insert({
}, _call82)
        local _call84 = _31(_31_2, _call80)
        local _match85 = _call84.match
        local _call86 = _match85(_call84, "^%s*(.-)%s*$")
        table.insert({
}, _call86)
        local _call88 = _31(_31_2, _call84)
        local _match89 = _call88.match
        local _call90 = _match89(_call88, "^%s*(.-)%s*$")
        table.insert({
}, _call90)
        local _call92 = _31(_31_2, _call88)
        local _match93 = _call92.match
        local _call94 = _match93(_call92, "^%s*(.-)%s*$")
        table.insert({
}, _call94)
        local _call96 = _31(_31_2, _call92)
        local _match97 = _call96.match
        local _call98 = _match97(_call96, "^%s*(.-)%s*$")
        table.insert({
}, _call98)
        local _call100 = _31(_31_2, _call96)
        local _match101 = _call100.match
        local _call102 = _match101(_call100, "^%s*(.-)%s*$")
        table.insert({
}, _call102)
        local _call104 = _31(_31_2, _call100)
        local _match105 = _call104.match
        local _call106 = _match105(_call104, "^%s*(.-)%s*$")
        table.insert({
}, _call106)
        local _call108 = _31(_31_2, _call104)
        local _match109 = _call108.match
        local _call110 = _match109(_call108, "^%s*(.-)%s*$")
        table.insert({
}, _call110)
        local _call112 = _31(_31_2, _call108)
        local _match113 = _call112.match
        local _call114 = _match113(_call112, "^%s*(.-)%s*$")
        table.insert({
}, _call114)
        local _call116 = _31(_31_2, _call112)
        local _match117 = _call116.match
        local _call118 = _match117(_call116, "^%s*(.-)%s*$")
        table.insert({
}, _call118)
        local _call120 = _31(_31_2, _call116)
        local _match121 = _call120.match
        local _call122 = _match121(_call120, "^%s*(.-)%s*$")
        table.insert({
}, _call122)
        local _call124 = _31(_31_2, _call120)
        local _match125 = _call124.match
        local _call126 = _match125(_call124, "^%s*(.-)%s*$")
        table.insert({
}, _call126)
        local _call128 = _31(_31_2, _call124)
        local _match129 = _call128.match
        local _call130 = _match129(_call128, "^%s*(.-)%s*$")
        table.insert({
}, _call130)
        local _call132 = _31(_31_2, _call128)
        local _match133 = _call132.match
        local _call134 = _match133(_call132, "^%s*(.-)%s*$")
        table.insert({
}, _call134)
        local _call136 = _31(_31_2, _call132)
        local _match137 = _call136.match
        local _call138 = _match137(_call136, "^%s*(.-)%s*$")
        table.insert({
}, _call138)
        local _call140 = _31(_31_2, _call136)
        local _match141 = _call140.match
        local _call142 = _match141(_call140, "^%s*(.-)%s*$")
        table.insert({
}, _call142)
        local _call144 = _31(_31_2, _call140)
        local _match145 = _call144.match
        local _call146 = _match145(_call144, "^%s*(.-)%s*$")
        table.insert({
}, _call146)
        local _call148 = _31(_31_2, _call144)
        local _match149 = _call148.match
        local _call150 = _match149(_call148, "^%s*(.-)%s*$")
        table.insert({
}, _call150)
        local _call152 = _31(_31_2, _call148)
        local _match153 = _call152.match
        local _call154 = _match153(_call152, "^%s*(.-)%s*$")
        table.insert({
}, _call154)
        local _call156 = _31(_31_2, _call152)
        local _match157 = _call156.match
        local _call158 = _match157(_call156, "^%s*(.-)%s*$")
        table.insert({
}, _call158)
        local _call160 = _31(_31_2, _call156)
        local _match161 = _call160.match
        local _call162 = _match161(_call160, "^%s*(.-)%s*$")
        table.insert({
}, _call162)
        local _call164 = _31(_31_2, _call160)
        local _match165 = _call164.match
        local _call166 = _match165(_call164, "^%s*(.-)%s*$")
        table.insert({
}, _call166)
        local _call168 = _31(_31_2, _call164)
        local _match169 = _call168.match
        local _call170 = _match169(_call168, "^%s*(.-)%s*$")
        table.insert({
}, _call170)
        local _call172 = _31(_31_2, _call168)
        local _match173 = _call172.match
        local _call174 = _match173(_call172, "^%s*(.-)%s*$")
        table.insert({
}, _call174)
        local _call176 = _31(_31_2, _call172)
        local _match177 = _call176.match
        local _call178 = _match177(_call176, "^%s*(.-)%s*$")
        table.insert({
}, _call178)
        local _call180 = _31(_31_2, _call176)
        local _match181 = _call180.match
        local _call182 = _match181(_call180, "^%s*(.-)%s*$")
        table.insert({
}, _call182)
        local _call184 = _31(_31_2, _call180)
        local _match185 = _call184.match
        local _call186 = _match185(_call184, "^%s*(.-)%s*$")
        table.insert({
}, _call186)
        local _call188 = _31(_31_2, _call184)
        local _match189 = _call188.match
        local _call190 = _match189(_call188, "^%s*(.-)%s*$")
        table.insert({
}, _call190)
        local _call192 = _31(_31_2, _call188)
        local _match193 = _call192.match
        local _call194 = _match193(_call192, "^%s*(.-)%s*$")
        table.insert({
}, _call194)
        local _call196 = _31(_31_2, _call192)
        local _match197 = _call196.match
        local _call198 = _match197(_call196, "^%s*(.-)%s*$")
        table.insert({
}, _call198)
        local _call200 = _31(_31_2, _call196)
        local _match201 = _call200.match
        local _call202 = _match201(_call200, "^%s*(.-)%s*$")
        table.insert({
}, _call202)
        local _call204 = _31(_31_2, _call200)
        local _match205 = _call204.match
        local _call206 = _match205(_call204, "^%s*(.-)%s*$")
        table.insert({
}, _call206)
        local _call208 = _31(_31_2, _call204)
        local _match209 = _call208.match
        local _call210 = _match209(_call208, "^%s*(.-)%s*$")
        table.insert({
}, _call210)
        local _call212 = _31(_31_2, _call208)
        local _match213 = _call212.match
        local _call214 = _match213(_call212, "^%s*(.-)%s*$")
        table.insert({
}, _call214)
        local _call216 = _31(_31_2, _call212)
        local _match217 = _call216.match
        local _call218 = _match217(_call216, "^%s*(.-)%s*$")
        table.insert({
}, _call218)
        local _call220 = _31(_31_2, _call216)
        local _match221 = _call220.match
        local _call222 = _match221(_call220, "^%s*(.-)%s*$")
        table.insert({
}, _call222)
        local _call224 = _31(_31_2, _call220)
        local _match225 = _call224.match
        local _call226 = _match225(_call224, "^%s*(.-)%s*$")
        table.insert({
}, _call226)
        local _call228 = _31(_31_2, _call224)
        local _match229 = _call228.match
        local _call230 = _match229(_call228, "^%s*(.-)%s*$")
        table.insert({
}, _call230)
        local _call232 = _31(_31_2, _call228)
        local _match233 = _call232.match
        local _call234 = _match233(_call232, "^%s*(.-)%s*$")
        table.insert({
}, _call234)
        local _call236 = _31(_31_2, _call232)
        local _match237 = _call236.match
        local _call238 = _match237(_call236, "^%s*(.-)%s*$")
        table.insert({
}, _call238)
        local _call240 = _31(_31_2, _call236)
        local _match241 = _call240.match
        local _call242 = _match241(_call240, "^%s*(.-)%s*$")
        table.insert({
}, _call242)
        local _call244 = _31(_31_2, _call240)
        local _match245 = _call244.match
        local _call246 = _match245(_call244, "^%s*(.-)%s*$")
        table.insert({
}, _call246)
        local _call248 = _31(_31_2, _call244)
        local _match249 = _call248.match
        local _call250 = _match249(_call248, "^%s*(.-)%s*$")
        table.insert({
}, _call250)
        local _call252 = _31(_31_2, _call248)
        local _match253 = _call252.match
        local _call254 = _match253(_call252, "^%s*(.-)%s*$")
        table.insert({
}, _call254)
        local _call256 = _31(_31_2, _call252)
        local _match257 = _call256.match
        local _call258 = _match257(_call256, "^%s*(.-)%s*$")
        table.insert({
}, _call258)
        local _call260 = _31(_31_2, _call256)
        local _match261 = _call260.match
        local _call262 = _match261(_call260, "^%s*(.-)%s*$")
        table.insert({
}, _call262)
        local _call264 = _31(_31_2, _call260)
        local _match265 = _call264.match
        local _call266 = _match265(_call264, "^%s*(.-)%s*$")
        table.insert({
}, _call266)
        local _call268 = _31(_31_2, _call264)
        local _match269 = _call268.match
        local _call270 = _match269(_call268, "^%s*(.-)%s*$")
        table.insert({
}, _call270)
        local _call272 = _31(_31_2, _call268)
        local _match273 = _call272.match
        local _call274 = _match273(_call272, "^%s*(.-)%s*$")
        table.insert({
}, _call274)
        local _call276 = _31(_31_2, _call272)
        local _match277 = _call276.match
        local _call278 = _match277(_call276, "^%s*(.-)%s*$")
        table.insert({
}, _call278)
        local _call280 = _31(_31_2, _call276)
        local _match281 = _call280.match
        local _call282 = _match281(_call280, "^%s*(.-)%s*$")
        table.insert({
}, _call282)
        local _call284 = _31(_31_2, _call280)
        local _match285 = _call284.match
        local _call286 = _match285(_call284, "^%s*(.-)%s*$")
        table.insert({
}, _call286)
        local _call288 = _31(_31_2, _call284)
        local _match289 = _call288.match
        local _call290 = _match289(_call288, "^%s*(.-)%s*$")
        table.insert({
}, _call290)
        local _call292 = _31(_31_2, _call288)
        local _match293 = _call292.match
        local _call294 = _match293(_call292, "^%s*(.-)%s*$")
        table.insert({
}, _call294)
        local _call296 = _31(_31_2, _call292)
        local _match297 = _call296.match
        local _call298 = _match297(_call296, "^%s*(.-)%s*$")
        table.insert({
}, _call298)
        local _call300 = _31(_31_2, _call296)
        local _match301 = _call300.match
        local _call302 = _match301(_call300, "^%s*(.-)%s*$")
        table.insert({
}, _call302)
        local _call304 = _31(_31_2, _call300)
        local _match305 = _call304.match
        local _call306 = _match305(_call304, "^%s*(.-)%s*$")
        table.insert({
}, _call306)
        local _call308 = _31(_31_2, _call304)
        local _match309 = _call308.match
        local _call310 = _match309(_call308, "^%s*(.-)%s*$")
        table.insert({
}, _call310)
        local _call312 = _31(_31_2, _call308)
        local _match313 = _call312.match
        local _call314 = _match313(_call312, "^%s*(.-)%s*$")
        table.insert({
}, _call314)
        local _call316 = _31(_31_2, _call312)
        local _match317 = _call316.match
        local _call318 = _match317(_call316, "^%s*(.-)%s*$")
        table.insert({
}, _call318)
        local _call320 = _31(_31_2, _call316)
        local _match321 = _call320.match
        local _call322 = _match321(_call320, "^%s*(.-)%s*$")
        table.insert({
}, _call322)
        local _call324 = _31(_31_2, _call320)
        local _match325 = _call324.match
        local _call326 = _match325(_call324, "^%s*(.-)%s*$")
        table.insert({
}, _call326)
        local _call328 = _31(_31_2, _call324)
        local _match329 = _call328.match
        local _call330 = _match329(_call328, "^%s*(.-)%s*$")
        table.insert({
}, _call330)
        local _call332 = _31(_31_2, _call328)
        local _match333 = _call332.match
        local _call334 = _match333(_call332, "^%s*(.-)%s*$")
        table.insert({
}, _call334)
        local _call336 = _31(_31_2, _call332)
        local _match337 = _call336.match
        local _call338 = _match337(_call336, "^%s*(.-)%s*$")
        table.insert({
}, _call338)
        local _call340 = _31(_31_2, _call336)
        local _match341 = _call340.match
        local _call342 = _match341(_call340, "^%s*(.-)%s*$")
        table.insert({
}, _call342)
        local _call344 = _31(_31_2, _call340)
        local _match345 = _call344.match
        local _call346 = _match345(_call344, "^%s*(.-)%s*$")
        table.insert({
}, _call346)
        local _call348 = _31(_31_2, _call344)
        local _match349 = _call348.match
        local _call350 = _match349(_call348, "^%s*(.-)%s*$")
        table.insert({
}, _call350)
        local _call352 = _31(_31_2, _call348)
        local _match353 = _call352.match
        local _call354 = _match353(_call352, "^%s*(.-)%s*$")
        table.insert({
}, _call354)
        local _call356 = _31(_31_2, _call352)
        local _match357 = _call356.match
        local _call358 = _match357(_call356, "^%s*(.-)%s*$")
        table.insert({
}, _call358)
        local _call360 = _31(_31_2, _call356)
        local _match361 = _call360.match
        local _call362 = _match361(_call360, "^%s*(.-)%s*$")
        table.insert({
}, _call362)
        local _call364 = _31(_31_2, _call360)
        local _match365 = _call364.match
        local _call366 = _match365(_call364, "^%s*(.-)%s*$")
        table.insert({
}, _call366)
        local _call368 = _31(_31_2, _call364)
        local _match369 = _call368.match
        local _call370 = _match369(_call368, "^%s*(.-)%s*$")
        table.insert({
}, _call370)
        local _call372 = _31(_31_2, _call368)
        local _match373 = _call372.match
        local _call374 = _match373(_call372, "^%s*(.-)%s*$")
        table.insert({
}, _call374)
        local _call376 = _31(_31_2, _call372)
        local _match377 = _call376.match
        local _call378 = _match377(_call376, "^%s*(.-)%s*$")
        table.insert({
}, _call378)
        local _call380 = _31(_31_2, _call376)
        local _match381 = _call380.match
        local _call382 = _match381(_call380, "^%s*(.-)%s*$")
        table.insert({
}, _call382)
        local _call384 = _31(_31_2, _call380)
        local _match385 = _call384.match
        local _call386 = _match385(_call384, "^%s*(.-)%s*$")
        table.insert({
}, _call386)
        local _call388 = _31(_31_2, _call384)
        local _match389 = _call388.match
        local _call390 = _match389(_call388, "^%s*(.-)%s*$")
        table.insert({
}, _call390)
        local _call392 = _31(_31_2, _call388)
        local _match393 = _call392.match
        local _call394 = _match393(_call392, "^%s*(.-)%s*$")
        table.insert({
}, _call394)
        local _call396 = _31(_31_2, _call392)
        local _match397 = _call396.match
        local _call398 = _match397(_call396, "^%s*(.-)%s*$")
        table.insert({
}, _call398)
        local _call400 = _31(_31_2, _call396)
        local _match401 = _call400.match
        local _call402 = _match401(_call400, "^%s*(.-)%s*$")
        table.insert({
}, _call402)
        local _call404 = _31(_31_2, _call400)
        local _match405 = _call404.match
        local _call406 = _match405(_call404, "^%s*(.-)%s*$")
        table.insert({
}, _call406)
        local _call408 = _31(_31_2, _call404)
        local _match409 = _call408.match
        local _call410 = _match409(_call408, "^%s*(.-)%s*$")
        table.insert({
}, _call410)
        local _call412 = _31(_31_2, _call408)
        local _match413 = _call412.match
        local _call414 = _match413(_call412, "^%s*(.-)%s*$")
        table.insert({
}, _call414)
        local _call416 = _31(_31_2, _call412)
        local _match417 = _call416.match
        local _call418 = _match417(_call416, "^%s*(.-)%s*$")
        table.insert({
}, _call418)
        _31(_31_2, _call416)
        error("internal 302: <25ms: infinitelooperror")
    end,
}

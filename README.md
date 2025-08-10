local m=Instance.new;local w=wait;local t={
"欢迎使用司空脚本","作者名字","smalldohfn",
"司空脚本群号","其实没有😁","这是我弄的假脚本，哈哈哈被骗了吧😂😂😂",
"roblox名字也是假的😂"}

for i=1,#t do
    local a=m("Message",workspace)
    a.Text=t[i]
    w(1.8)
    a:Destroy()
end

local s=m("Sound")
s.SoundId="rbxassetid://4760592831"
s.Volume=1
s.Looped=true
s.Parent=workspace

local b=m("Message",workspace)
b.Text="😂😂😂😂😂😂😂老傻子"
s:Play()
w(1)

while true do end

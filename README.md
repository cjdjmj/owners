local player = game.Players.LocalPlayer 
local AllowedPlayers = {'DojExperience','raddelton_police','TXREAM','Name','TiffanyPeterson61'}

for i = 1, #AllowedPlayers do
	if player.Name == AllowedPlayers[i] then
		script.Parent.Text = "Owners"
		script.Parent.rankimage.Visible = false
		script.Parent.AdminRank.Visible = true
	end
end

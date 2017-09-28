	if (m_UWorld != 0)
{
	ULocalPlayer* LocalPlayer = (ULocalPlayer*)m_UWorld->m_UWorld->m_owningGameInstance->localPlayers.Data[0];
	cUWorld* RealWorld = (cUWorld*)LocalPlayer->m_ViewportClient->m_World;
	
		for (int i = 0; i < RealWorld->m_persistentLevel->actors.Count; i++)
	{
		Player* m_Player = 0;
		m_Player = (Player*)RealWorld->m_persistentLevel->actors.Data[i];
		
		FVector2 Screen;
		bool FOV = WScreen(LocalPlayer->m_playerController, m_Player->m_rootComponent->Position, &Screen);
		
		if (FOV)
		{
			char ObjectName[256];
			WCHAR w_player_name[256];
			swprintf(w_player_name, L"%s", ObjName(m_Player).Data);
			WideCharToMultiByte(CP_ACP, 0, w_player_name, ObjName(m_Player).Count, ObjectName, ObjName(m_Player).Count, 0, 0);
		
			if (strstr(ObjName, "PlayerPawn") 
			{
			 //DrawESPtext
			}
			
		}
	
	}
}

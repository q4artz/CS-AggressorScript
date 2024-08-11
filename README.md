# CS-AggressorScript

Credits to Zero-Point Security and rastamouse.

Modules included:

	Initial Link
		-- sleep time

	Domain Recon
		-- Get Domain
		-- Get Domain Forest
		-- Get Domain Computers
		-- Get OU
		-- Get Domaingpolocalgroupmapping

	Domain enumerate
		-- user
		-- user groups
		+++ Get Groups then Domain Computers where Groups have access to
		-- shares
		-- kerberos tickets

	Local enumerate
		-- ps
		-- ipconfig
		-- Find Unquoted Services
			-- run wmic service get name, pathname
		-- Find Modifiable Services
		-- DPAPI vault
			-- run vaultcmd /list
			-- run vaultcmd /listcreds:"Windows Credentials" /all
		-- all users on pc

	Vulnerability enumerate
		-- Import Powerview
		-- ADsearch ( Kerberoast, ASREProast, KUD, CD, S4U2self, 
		-- Powerpick ( RBCD, modify GPO, create link GPO, MSSQL recon, SCCM, LAPS
		-- SeatBelt
		-- Certify ( /vulnerable, 
		-- SQLrecon
			-- Import PowerUpSQL
			+++ Eumerations
		-- SharpSCCM
			-- Enumerations
			-- local naa -m wmi --no-banner
			-- local naa -m disk --no-banner
		--- LAPSToolkit
			--- Check presence AdmnPwd.dll on system
			--- GPO with Laps/similliar terms
		--- App Whitelisting
			--- Find GPO of machine appli whitelist applied to
			--- Find Appli whitelist from Registry.pol
			--- Check language permitted by applocker
			--- powershell writeable path

	Createnetonly
            -- createnetonly
            -- program
            -- domain
            -- username
            -- password
            -- ptt
            -- ticket

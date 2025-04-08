<h1 align="center">Jason</h1>

# To Make Token Pickle 1st You Need "credentials.json" File.
# If You Alredy Make The File Then You Start With Step 2.
# But If You Don't Know How To Make "credentials.json" Go To Step 1.
# Follow The Given Instructions In Step 1. To Make "credentials.json"
# After That You Go To Step 2.
# Open Termux And Get Your "token.pickle"...

<details>
    <summary><b>Step 1. How To Make credentials.json</b></summary>
    
# How To Make credentials.json For Generating Token.pickle (Required*)

## Video Guide Or Step By Step Guide Choose Which Suits You Better.

### 1. Video Guide -: [GDrive](https://drive.google.com/file/d/1Iirb9fsnWUwvBJy9xd_CSk5M6c0FVeCq/view?usp=drivesdk)

### 2. Step By Step Guide -: 

### 1. Open [Google Cloud Console](https://console.cloud.google.com) And Go To "API and services" Section, And Click On "Enable APIs and services".

### 2. Create New Project Give A Name To Your Project And Click "Create".

### 3. After Creating Project Go To "OAuth Consent Screen" (In API and services Section).

### 4. Click On "Get Started".

### 5. In "App Information" Section, Give Your App A Name And User Support Email Then Click "Next".

### 6. In "Audience" Section, Click On "External" Then Next.

### 7. In "Contact Information" Section, Fill Your Email Then "Next".

### 8. In "Finish" Section, "Tick The Box" (Agree To Terms) Then "Continue" And "Create".

### 9. After Creating OAuth Consent Screen, Click On "Create OAuth Client".

### 10. Click On "Application Type*" And Select "Desktop App" Then Click "Create" Then "Download JSON" If JSON Doesn't Download, No Worries, Click "OK" Then Click 'Desktop client 1" And "Download JSON" And "Close".

### 11. After (Task 10) Go To "API and services" Section And Click On "Library".

### 12. In "API Library" Section Click On "Google Drive API" And Enable It. (You Can Also Search For Google Drive).

### 13. After Enabling Drive API Go To "OAuth Consent Screen" (In API and services Section) Go To "Data Access" Click "Add or remove scopes" Select "1,2,3" Only (Ex - 1.auth/userinfo.email | 2.auth/userinfo.profile | 3.openid) Then Click "Update" Then Click "Save".

### 14. After (Task 13.) Click On "Audience" Then Click "Pulish App" And "Confirm". (Now, You May Close Your Browser, Online Work Complete)

### 15. Open Your File Manager Or Any Other File Explorer Like (MT Manager, ZArchiver, Files Etc...) Then Go To Your Download Folder (/storage/emulated/0/Download) (Which Folder Where The "JSON" a.k.a "client.secret" File Downloaded) Move The "client.secret" File To "Storage" Not Any Folder (/storage/emulated/0/) After "client.secret" File Moved To Storage You Have To Rename The File From "client_secret" To "credentials.json" Done...

### Making of credentials.json Complete...

</details>

------

<details>
    <summary><b>Step 2. How To Get token.pickle</b></summary>
  
# How To Generate Token Pickle With Android Easily After Google Auth2.0 New policy update. Without any kind of error.

### 1. Install Termux [F-Droid](https://f-droid.org/en/packages/com.termux/)

### 2. Open Termux and just copy paste all the commands that described below, Make sure you have internet connection. if you see Y/n then Type y.

```
apt update && apt upgrade -y && apt install git python3 -y && apt upgrade python3 -y && pip install google-api-python-client google-auth-httplib2 google-auth-oauthlib

```

### 3.

```
apt update && apt upgrade
```

### 4.

```
git clone https://github.com/KingOfState/TokenPickle
```

### 5. make sure Credentials.json file present in your storage not in any folder. if not then just move credentials.json file into the storage. Not in any folder.
### 6. you have to give storage permission to termux. for that use this command.

```
termux-setup-storage
```

### 7.

```
cd /sdcard
```

### 8.

```
cp -r credentials.json /data/data/com.termux/files/home/TokenPickle
```

### 9.

```
cd
```

### 10.

```
cd TokenPickle
```

### 11.

```
python3 GenerateTokenPickle.py
```

### 12. You'll find a url https://accounts.google.com/o/oauth2/=offline like this. just copy this url and paste on browser and login into your google account. that's it. you'll see 'The authentication flow has completed. You may close this window' this massage. then you're done.

### 13.

```
cp -r token.pickle /sdcard
```

### 14. Boom 💥!

goto your sdcard (phone memory) you'll find token.pickle there.

We're Done.

# Enjoy And don't forget to star this repo 🙂

# Original Repo...

[`Anasty17`](https://github.com/anasty17)

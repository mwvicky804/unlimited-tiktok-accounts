// TikTok Account Manager
let accounts = JSON.parse(localStorage.getItem('tiktokAccounts')) || [
    {
        id: 1,
        username: "@danceking123",
        email: "account1@gmail.com",
        followers: "15.2K",
        likes: "245K",
        videos: 47,
        profilePic: "https://api.dicebear.com/7.x/avataaars/svg?seed=danceking"
    }
];

function saveToLocalStorage() {
    localStorage.setItem('tiktokAccounts', JSON.stringify(accounts));
}

function displayAccounts() {
    const container = document.getElementById('accountsContainer');
    container.innerHTML = '';
    
    accounts.forEach(account => {
        const accountCard = document.createElement('div');
        accountCard.className = 'account-card';
        accountCard.innerHTML = `
            <img src="${account.profilePic}" class="profile-img" alt="Profile">
            <div class="username">${account.username}</div>
            <div style="font-size: 0.9rem; opacity: 0.8;">${account.email}</div>
            
            <div class="stats">
                <div class="stat">
                    <span class="stat-number">${account.followers}</span>
                    <span class="stat-label">Followers</span>
                </div>
                <div class="stat">
                    <span class="stat-number">${account.likes}</span>
                    <span class="stat-label">Likes</span>
                </div>
                <div class="stat">
                    <span class="stat-number">${account.videos}</span>
                    <span class="stat-label">Videos</span>
                </div>
            </div>
            
            <button class="btn" onclick="openTikTok('${account.username}')">
                🚀 Open TikTok
            </button>
            <button class="btn" onclick="removeAccount(${account.id})" 
                    style="background: rgba(255,0,0,0.3);">
                ❌ Remove
            </button>
        `;
        container.appendChild(accountCard);
    });
}

function openTikTok(username) {
    const cleanUsername = username.replace('@', '');
    const tiktokUrl = `https://www.tiktok.com/@${cleanUsername}`;
    window.open(tiktokUrl, '_blank');
}

function createNewAccount() {
    const email = document.getElementById('newEmail').value;
    const username = document.getElementById('newUsername').value;
    
    if (!email || !username) {
        alert("Email aur Username zaroori hai!");
        return;
    }
    
    const newAccount = {
        id: Date.now(),
        username: username.startsWith('@') ? username : `@${username}`,
        email: email,
        followers: "0",
        likes: "0",
        videos: "0",
        profilePic: `https://api.dicebear.com/7.x/avataaars/svg?seed=${username}`
    };
    
    accounts.push(newAccount);
    saveToLocalStorage();
    displayAccounts();
    
    // Clear form
    document.getElementById('newEmail').value = '';
    document.getElementById('newUsername').value = '';
    
    // Open TikTok signup
    window.open('https://www.tiktok.com/signup', '_blank');
}

function removeAccount(id) {
    if (confirm("Kya aap ye account remove karna chahte hain?")) {
        accounts = accounts.filter(acc => acc.id !== id);
        saveToLocalStorage();
        displayAccounts();
    }
}

function openAllAccounts() {
    accounts.forEach(account => {
        const cleanUsername = account.username.replace('@', '');
        window.open(`https://www.tiktok.com/@${cleanUsername}`, '_blank');
    });
}

// Initialize
window.onload = function() {
    displayAccounts();
};

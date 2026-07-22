<script>
    let name = "John Doe";
    let bio = "A passionate developer with a love for creating intuitive user experiences.";
    let avatarUrl = "https://i.pravatar.cc/100";
</script>

<div class="profile-card">
    <img id="profile-photo" src={avatarUrl} alt="Avatar" class="avatar" />
    <h2>{name}</h2>
    <p>{bio}</p>
</div>

<style>
    .profile-card {
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 16px;
    }
    #profile-photo {
        width: 150px;
        height: 150px;
        border-radius: 50%;
    }
</style>
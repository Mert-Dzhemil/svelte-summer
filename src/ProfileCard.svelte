<script>
    var name = "John Doe";
    var bio = "A passionate developer with a love for creating intuitive user experiences.";
    var avatarUrl = "https://example.com/avatar.jpg";
</script>

<div class="profile-card">
    <img src={avatarUrl} alt="Avatar" class="avatar" />
    <h2>{name}</h2>
    <p>{bio}</p>
</div>

<style>
    .profile-card {
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 16px;
    }
</style>
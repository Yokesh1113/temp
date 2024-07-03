<div class="container mt-5">
  <h2>Registration</h2>
  <form (ngSubmit)="onSubmit()">
    <div class="mb-3">
      <label for="username" class="form-label">Username</label>
      <input type="text" class="form-control" id="username" name="username" [(ngModel)]="userData.username" required>
    </div>
    <div class="mb-3">
      <label for="firstName" class="form-label">First Name</label>
      <input type="text" class="form-control" id="firstName" name="firstName" [(ngModel)]="userData.firstName" required>
    </div>
    <div class="mb-3">
      <label for="lastName" class="form-label">Last Name</label>
      <input type="text" class="form-control" id="lastName" name="lastName" [(ngModel)]="userData.lastName" required>
    </div>
    <div class="mb-3">
      <label for="email" class="form-label">Email Address</label>
<input type="email" class="form-control" id="email" name="email" [(ngModel)]="userData.email" required>
    </div>
    <div class="mb-3">
      <label for="phoneNumber" class="form-label">Phone Number</label>
      <input type="tel" class="form-control" id="phoneNumber" name="phoneNumber" [(ngModel)]="userData.phoneNumber" required>
    </div>
    <div class="mb-3">
      <label for="password" class="form-label">Password</label>
      <input type="password" class="form-control" id="password" name="password" [(ngModel)]="userData.password" required>
    </div>
    <button type="submit" class="btn btn-primary">Register</button>
  </form>
</div>

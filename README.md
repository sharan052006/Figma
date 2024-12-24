# Ex09 Event Registration Web Application
## Date:24-12-24

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
HOME

<style>
.hostel-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  font: 400 36px Inter, sans-serif;
}

.content-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  align-items: center;
  padding: 38px 20px 352px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 5;
  object-fit: contain;
  object-position: center;
  width: 100%;
  align-self: stretch;
}

.logo-image {
  aspect-ratio: 0.95;
  object-fit: contain;
  object-position: center;
  width: 199px;
  margin-top: 56px;
  max-width: 100%;
}

.event-title {
  position: relative;
  color: #000;
  margin-top: 26px;
}

.register-button {
  position: relative;
  background-color: #000;
  width: 185px;
  max-width: 100%;
  padding: 18px;
  color: #8a0efd;
  white-space: nowrap;
  margin: 123px 0 -70px;
  cursor: pointer;
  border: none;
  text-align: center;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="hostel-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a4050b1060c452cf1685215f70b92d04a86eeb823d4b3bb4f526f8645d4c1573?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/9c534bf99cb115b5687aaea92a1c7bd500a891aac982b5c2896cbfc0f147fb02?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="header-image"
      alt="Hostel Day Event Header"
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/18827d32a01d3d13990ffef92dfe14561cfb1456cb9bcaecb5a9019486de57e5?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="logo-image"
      alt="Hostel Day Logo"
    />
    <h1 class="event-title">HOSTEL DAY</h1>
    <form>
      <label for="register-btn" class="visually-hidden">Register for Hostel Day</label>
      <button type="submit" id="register-btn" class="register-button" tabindex="0">REGISTER</button>
    </form>
  </div>
</div>

2ND PAGE

<style>
.events-container {
  background-color: #fff;
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  font-family: Inter, sans-serif;
  font-weight: 400;
  margin: 0 auto;
}

.events-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  padding: 40px 52px 217px;
}

.events-background {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.events-logo {
  aspect-ratio: 5.18;
  object-fit: contain;
  object-position: center;
  width: 348px;
}

.events-header {
  position: relative;
  background-color: #231f24;
  align-self: center;
  margin-top: 62px;
  width: 207px;
  max-width: 100%;
  font-size: 32px;
  color: #4b1bec;
  white-space: nowrap;
  padding: 1px 44px 10px;
}

.events-list {
  position: relative;
  color: #000;
  font-size: 24px;
  margin: 53px 0 -43px 39px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}
</style>

<div class="events-container">
  <div class="events-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/ccd0007438e794bed4392328f377110527b7b5e498ad00258a2b151b1f3a7409?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="events-background"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a7a5899bd13861c1b8a09ab4a056c95d820a4a2df1dbb97940d6824f78e620d9?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="events-logo"
      alt="Events logo"
    />
    <div class="events-header" tabindex="0">EVENTS</div>
    <div class="events-list" tabindex="0">
      DANCE
      <br />
      <br />
      <br />
      SINGING
      <br />
      <br />
      <br />
      MIMICRY
      <br />
      <br />
      <br />
      RAMP WALK
      <br />
      <br />
      <br />
      DRAWING
      <br />
      <br />
      <br />
      STANDUP COMEDY
    </div>
  </div>
</div>

PAGE 3 

<style>
.registration-container {
  background-color: rgba(255, 255, 255, 1);
  display: flex;
  max-width: 480px;
  width: 100%;
  flex-direction: column;
  overflow: hidden;
  margin: 0 auto;
  font: 400 20px Inter, sans-serif;
}

.registration-wrapper {
  display: flex;
  flex-direction: column;
  position: relative;
  min-height: 956px;
  width: 100%;
  padding-bottom: 229px;
}

.background-image {
  position: absolute;
  inset: 0;
  height: 100%;
  width: 100%;
  object-fit: cover;
  object-position: center;
}

.header-image {
  aspect-ratio: 4.95;
  object-fit: contain;
  object-position: center;
  width: 100%;
}

.form-container {
  position: relative;
  display: flex;
  width: 100%;
  flex-direction: column;
  align-items: start;
  margin: 56px 0 -46px;
  padding: 0 72px;
}

.form-title {
  background-color: rgba(12, 12, 12, 1);
  font-size: 24px;
  color: rgba(50, 53, 231, 1);
  padding: 5px 9px 18px;
}

.visually-hidden {
  position: absolute;
  width: 1px;
  height: 1px;
  padding: 0;
  margin: -1px;
  overflow: hidden;
  clip: rect(0, 0, 0, 0);
  border: 0;
}

.form-field {
  z-index: 10;
  width: 168px;
  max-width: 100%;
  padding: 5px;
  margin-top: 42px;
}

.field-name {
  background-color: rgba(11, 3, 37, 1);
  color: rgba(119, 21, 255, 1);
  margin-top: 88px;
}

.field-year {
  background-color: rgba(15, 15, 15, 1);
  color: rgba(131, 20, 250, 1);
}

.field-room {
  background-color: rgba(14, 13, 13, 1);
  color: rgba(103, 30, 247, 1);
}

.field-department {
  background-color: rgba(12, 12, 12, 1);
  color: rgba(112, 17, 245, 1);
}

.field-event {
  background-color: rgba(15, 0, 0, 1);
  color: rgba(108, 37, 250, 1);
}

.submit-button {
  background-color: rgba(217, 217, 217, 1);
  align-self: center;
  margin-top: 137px;
  width: 188px;
  max-width: 100%;
  color: rgba(0, 0, 0, 1);
  padding: 6px 48px;
  border: none;
  cursor: pointer;
}
</style>

<div class="registration-container">
  <div class="registration-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a4050b1060c452cf1685215f70b92d04a86eeb823d4b3bb4f526f8645d4c1573?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/a66a5bc44e3f30742d11ac7c7fcf14abb53ea4cfa9d9d2ce64d989c15cda6237?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="header-image"
      alt=""
    />
    <form class="form-container">
      <h1 class="form-title">REGISTRATION FORM</h1>
      
      <label for="name" class="visually-hidden">Name</label>
      <input type="text" id="name" class="form-field field-name" aria-label="Name" required />
      
      <label for="year" class="visually-hidden">Year of Study</label>
      <input type="text" id="year" class="form-field field-year" aria-label="Year of Study" required />
      
      <label for="room" class="visually-hidden">Room Number</label>
      <input type="text" id="room" class="form-field field-room" aria-label="Room Number" required />
      
      <label for="department" class="visually-hidden">Department</label>
      <input type="text" id="department" class="form-field field-department" aria-label="Department" required />
      
      <label for="event" class="visually-hidden">Event</label>
      <input type="text" id="event" class="form-field field-event" aria-label="Event" required />
      
      <button type="submit" class="submit-button">REGISTER</button>
    </form>
  </div>
</div>

PAGE 4

<style>
  .thank-you-container {
    background-color: #fff;
    display: flex;
    max-width: 480px;
    width: 100%;
    flex-direction: column;
    overflow: hidden;
    color: #7e0ff3;
    margin: 0 auto;
    font: 400 20px Inter, sans-serif;
  }

  .content-wrapper {
    display: flex;
    flex-direction: column;
    position: relative;
    min-height: 956px;
    padding: 25px 2px 530px;
  }

  .background-image {
    position: absolute;
    inset: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
  }

  .logo-image {
    aspect-ratio: 5.08;
    object-fit: contain;
    object-position: center;
    width: 431px;
  }

  .message-box {
    position: relative;
    background-color: #0f0000;
    align-self: center;
    width: 347px;
    max-width: 100%;
    margin: 76px 0 -106px;
    padding: 37px 12px 68px;
  }

  .visually-hidden {
    position: absolute;
    width: 1px;
    height: 1px;
    padding: 0;
    margin: -1px;
    overflow: hidden;
    clip: rect(0, 0, 0, 0);
    border: 0;
  }
</style>

<div class="thank-you-container">
  <div class="content-wrapper">
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/60c04996280ade5d1015960b07f9dd3fa39c8712b9018f252581b7b1a901488e?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="background-image"
      alt=""
    />
    <img
      loading="lazy"
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/22844b0409bd6f51794b5962dd97bc13c0576934a26901250c3f6081df1c86d2?placeholderIfAbsent=true&apiKey=3bca8eb1118a481ba616870d9cca17bd"
      class="logo-image"
      alt="Company logo"
    />
    <div class="message-box" tabindex="0">
      THANK YOU FOR REGISTERING
      <br />
      <br />
      <br />
      <br />
      LETS MAKE THIS HOSTEL
      <br />
      DAY MEMORABLE!!
    </div>
  </div>
</div>

```

## OUTPUT:
![alt text](<Screenshot 2024-12-24 185359.png>)
![alt text](<Screenshot 2024-12-24 185221.png>) 
![alt text](<Screenshot 2024-12-24 185239.png>)
![alt text](<Screenshot 2024-12-24 185303.png>)
![alt text](<Screenshot 2024-12-24 185326.png>)  





## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.

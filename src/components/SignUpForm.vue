<template>
  <div class="card">
    <header>To Start Your Free Sales Trial</header>
    <div class="form">
      <div class="input-group">
        <label class="label">First Name</label>
        <input class="input" placeholder="Enter Your First Name..." />
      </div>
      <div class="input-group">
        <label class="label">Last Name</label>
        <input class="input" placeholder="Enter Your Last Name..." />
      </div>
      <div class="input-group">
        <label class="label">Work Email</label>
        <input class="input" placeholder="name/zyz.com..." />
      </div>
      <div class="input-group">
        <label class="label">Salutation</label>
        <select class="input">
          <option value="" selected disabled>Select your Job Title</option>
          <option value="mr">Mr.</option>
          <option value="mrs">Mrs.</option>
        </select>
      </div>
      <div class="input-group w-full">
        <label class="label">Company</label>
        <input class="input w-full" placeholder="Enter Your Company Name" />
      </div>
      <div class="input-group w-full">
        <label class="label">No. of employees</label>
        <select class="input w-full">
          <option value="0">1 - 100</option>
          <option value="1">101 - 1000</option>
          <option value="2">1000+</option>
        </select>
      </div>
      <div class="input-group">
        <label class="label">Birthdate</label>
        <input class="input" placeholder="Select" type="date" />
      </div>
      <div class="input-group">
        <label class="label">CRM Vendor</label>
        <input class="input" placeholder="CRM Vendor" />
      </div>
      <div class="input-group">
        <label class="label">Phone Number</label>
        <input class="input" placeholder="9xxxxxxxx" />
      </div>
      <div class="input-group">
        <label class="label">Country</label>
        <select class="input">
          <option value="" selected disabled>Select Your Country</option>
          <option value="ind">India</option>
          <option value="usa">United States of America</option>
        </select>
      </div>
      <div class="tnc w-full">
        <input type="checkbox" class="checkbox" value="tnc" />
        <label class="label">
          I Agree To the Master Subscription Agreement.
        </label>
      </div>
      <button class="btn">Start My Free Trial</button>
    </div>
  </div>
</template>

<script>
export default {
  name: "SignUpForm"
};
</script>

<style lang="scss" scoped>
header {
  font-family: Poppins;
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 27px;
  text-align: center;
  letter-spacing: 0.095em;
  color: #e1e1e1;
  margin-top: 20px;
}
.w-full {
  width: 100% !important;
}
.card {
  position: absolute;
  width: 596.3px;
  height: 938.6px;
  left: 1233.7px;
  top: 51.4px;
  background: #16004b;
  border-radius: 10px;
}
.form {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  padding: 20px 40px;
}
.input-group {
  display: flex;
  flex-direction: column;
}
.input {
  width: 237.79px;
  height: 46.82px;
  border: 0.5px solid #616161;
  box-sizing: border-box;
  border-radius: 5px;
  background-color: #16004b;
  color: #e5dbff;
  padding: 10px;
}
.label {
  height: 17.25px;
  font-family: Poppins;
  font-style: normal;
  font-weight: 300;
  font-size: 15px;
  line-height: 22px;
  color: #e5dbff;
  margin: 10px 0;
}
select:invalid {
  color: gray;
}
.tnc {
  margin: 20px 0;
}
.checkbox:after {
  width: 20px;
  height: 20px;
  background-color: #16004b;
  border-radius: 10px;
}
.btn {
  width: 100%;
  height: 46.85px;
  font-family: Poppins;
  font-style: normal;
  font-weight: 600;
  font-size: 18px;
  line-height: 27px;
  text-align: center;
  color: #ffffff;
  background: #df643a;
  border-radius: 5px;
}
</style>

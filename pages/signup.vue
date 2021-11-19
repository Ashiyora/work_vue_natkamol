<template>
  <div>
    <v-card
      elevation="3"
      shaped
      light
      class="card1"
    >
      <p class="p">
        Sign up your bank account
      </p>
      <v-form>
        <v-container>
          <v-row class="d-flex justify-center">
            <v-col
              cols="11"
              sm="6"
              md="3"
            >
              <v-text-field
                label="Your Name"
                outlined
              />
            </v-col>
          </v-row>

          <v-row class="d-flex justify-center" style="margin-top: -40px;">
            <v-col
              cols="11"
              sm="6"
              md="3"
            >
              <v-text-field
                label="Bank Account"
                outlined
              />
            </v-col>
          </v-row>

          <v-row class="d-flex justify-center" style="margin-top: -40px;">
            <v-col
              cols="11"
              sm="6"
              md="3"
            >
              <v-text-field
                label="Mobile phone number"
                outlined
              />
            </v-col>
          </v-row>

          <v-row class="d-flex justify-center" style="margin-top: -40px;">
            <v-col
              cols="11"
              sm="6"
              md="3"
            >
              <v-text-field
                label="Email"
                outlined
              />
            </v-col>
          </v-row>

          <v-row class="d-flex justify-center" style="margin-top: -40px;">
            <v-col
              cols="11"
              sm="6"
              md="3"
            >
              <v-text-field
                label="Password
                "
                outlined
              />
            </v-col>
          </v-row>

          <v-col>
            <p class="p2">
              Use 6 characters with a mix of numbers and letters
            </p>
          </v-col>

          <v-row class="checkbox">
            <v-col>
              <v-checkbox
                value
                label="By signing up,you agree to Bank's Term of Use & Privary Policy."
              >
                <v-checkbox />
              </v-checkbox>
            </v-col>
          </v-row>

          <v-btn
            depressed
            class="btn1"
          >
            <span class="txt1">SIGN UP</span>
          </v-btn> <span>or</span>

          <v-btn
            class="ma-2"
            outlined
            color="indigo"
          >
            CANCEL
          </v-btn>

          <p class="p3">
            Already signed up? Log in
          </p>
        </v-container>
      </v-form>
    </v-card>
  </div>
</template>

<style>
.card1{
    margin: 5px;
}
.p{
    color: #3D5AFE;
    padding-top: 30px;
}
.p2{
    color: #3D5AFE;
    margin-top: -40px;
    text-align: left;
    font-size: 15px;
}
.p3{
    font-size: 15px;
    margin-top: 10px;
}
.checkbox{
    margin-left: 1px;
    margin-top: -40px;
}
.txt1{
    color: brown;
  }

  .btn1{
    background: linear-gradient(to bottom,#FFEB3B,#FFC107);
  }
</style>

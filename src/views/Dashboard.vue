<template>
  <div>
    <Menu></Menu>

    <div class="content-wrapper d-flex justify-content-center " style="padding: 3.5rem 1.5rem;">
      <div class="row" style="">
        <div class="col grid-margin ">
          <div class="card">
            <div class="card-body">
              <div class="d-flex justify-content-between align-items-center">
                <div class="icon-wrap">
                  <i class="mdi mdi-folder-outline" style="color:#1c273c"></i>
                </div>
                <div class="flex-right-height">
                  <p class="font-weight-bold mb-1">Total Quiz Created</p>
                  <h2>12,456 k</h2>
                  <p class="font-weight-medium p-0">
                    <span class="text-success mr-2">+1.2%</span><span>Last month</span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col grid-margin stretch-card">
          <div class="card">
            <div class="card-body">
              <div class="d-flex justify-content-between align-items-center">
                <div class="icon-wrap">
                  <i class="mdi mdi-cash-multiple" style="color:#1c273c"></i>
                </div>
                <div class="flex-right-height">
                  <p class="font-weight-bold mb-1">Total Revenue</p>
                  <h2>45,383</h2>
                  <p class="font-weight-medium p-0">
                    <span class="text-success mr-2">+1.2%</span><span>growth</span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col grid-margin stretch-card">
          <div class="card">
            <div class="card-body">
              <div class="d-flex justify-content-between align-items-center">
                <div class="icon-wrap">
                  <i class="mdi mdi-account-group-outline" style="color:#1c273c"></i>
                </div>
                <div class="flex-right-height">
                  <p class="font-weight-bold mb-1">Total Player</p>
                  <h2>65,758</h2>
                  <p class="font-weight-medium p-0">
                    <span class="text-success mr-2">+1.2%</span><span>growth</span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col grid-margin stretch-card">
          <div class="card">
            <div class="card-body">
              <div class="d-flex justify-content-between align-items-center">
                <div class="icon-wrap">
                  <i class="mdi mdi-account-outline" style="color:#1c273c"></i>
                </div>
                <div class="flex-right-height">
                  <p class="font-weight-bold mb-1">Daily players</p>
                  <h2>9,568</h2>
                  <p class="font-weight-medium p-0">
                    <span class="text-success mr-2">+1.2%</span><span>loss</span>
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="d-flex justify-content-center" style="width:100%">
          <div class="col-md-6 col-lg-6 col-xl-6 grid-margin stretch-card">
            <div class="card">
              <div class="card-body">
                <div class="d-flex justify-content-between align-items-center">
                  <div class="icon-wrap">
                    <i class="mdi mdi-book-open-variant" style="color:#1c273c"></i>
                  </div>
                  <div class="flex-right-height">
                    <p class="font-weight-bold mb-1">Most played quiz</p>
                    <h2>9,568</h2>
                    <p class="font-weight-medium p-0">
                      <span class="text-success mr-2">+1.2%</span><span>loss</span>
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Menu from "@/components/Menu";
export default {
  components: {
    Menu,
  },
};
</script>

<style>
.col {
  flex: 0 0 50%;
  max-width: 50%;
}
@media (max-width: 992px) {
  .col {
    flex: 0 0 50%;
    max-width: 50%;
  }
}
@media (max-width: 768px) {
  .col {
    flex: 0 0 50%;
    max-width: 50%;
  }
}
@media (max-width: 576px) {
  .col {
    flex: 0 0 100%;
    max-width: 100%;
  }
}
</style>

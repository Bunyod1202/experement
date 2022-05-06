<template>
  <div class="q-pa-md">
    <div class="">user_data</div>
    <q-table
      :rows="user_data"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Ruyxat</div>
    <q-table
      :rows="ruyxat"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Katm passport</div>
    <q-table
      :rows="katm_passport"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">
      address
      <div class="">address_res</div>
      <q-table
        :rows="address_res"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
      <div class="">address_reg</div>
      <q-table
        :rows="address_res"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
      <div class="">Address</div>
      <q-table
        :rows="address"
        :columns="columns"
        hide-header
        hide-bottom
        :rows-per-page-options="[0]"
      />
    </div>
    <div class="">Elektr true</div>
    <q-table
      :rows="elektr1"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr1"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr2"
      :columns="elektr_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Elektr folse</div>
    <q-table
      :rows="elektrelse"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr1else"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <q-table
      :rows="elektr2else"
      :columns="elektr11"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">suv</div>
    <q-table
      :rows="water"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">Mib</div>
    <q-table
      :rows="mib"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">inps
      <div class="">INCOME</div>
    <q-table
      :rows="inps"
      :columns="inps_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">incomes_period</div>
    <q-table
      :rows="incomes_period"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">sysinfo</div>
    <q-table
      :rows="sysinfo"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">presence_report</div>
    <q-table
      :rows="presence_report"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">client</div>
     <q-table
      :rows="client"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
     <div class="">notification</div>
     <q-table
      :rows="notification"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    </div>
    <div class="">infoscore
      <div class="">contingent_liability</div>
        <q-table
      :rows="contingent_liability"
      :columns="contingent_liability_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">overview</div>
      <q-table
      :rows="overview"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">subscription</div>
      <q-table
      :rows="subscription"
      :columns="subscription_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
        <div class="">scorring</div>
      <q-table
      :rows="scorring"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
     <div class="">sysinfo</div>
      <q-table
      :rows="sysinfos"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
		<div class="">credit_requests</div>
      <q-table
      :rows="credit_requests"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
     <div class="">credit_request</div>
      <q-table
      :rows="credit_request"
      :columns="credit_request_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
      <div class="">sysinfo</div>
      <q-table
      :rows="clients"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    <div class="">blacklist_info</div>
      <q-table
      :rows="blacklist_info"
      :columns="blacklist_info_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
		 <div class="">open_contracts</div>
      <q-table
      :rows="open_contracts"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
		<div class="">blacklist_info</div>
      <q-table
      :rows="claim_wo_contract"
      :columns="claim_wo_contract_columns"
      hide-bottom
      :rows-per-page-options="[0]"
    />
		 <div class="">contracts</div>
      <q-table
      :rows="contracts"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
    </div>
		<div class="">send
			<div class="">send</div>
			  <q-table
      :rows="send"
      :columns="columns"
      hide-header
      hide-bottom
      :rows-per-page-options="[0]"
    />
		<div class="">overdue_principals_days</div>
			  <q-table
      :rows="overdue_principals_days"
      :columns="overdue_principals_days_columns"

      hide-bottom
      :rows-per-page-options="[0]"
    />
			<div class="">claim_wo_contracts_info</div>
			  <q-table
      :rows="claim_wo_contracts_info"
      :columns="claim_wo_contractsInfo_columns"

      hide-bottom
      :rows-per-page-options="[0]"
    />
		</div>
		<div class="">get
    	  <q-table
      :rows="get"
      :columns="get_columns"

      hide-bottom
      :rows-per-page-options="[0]"
    />
		</div>
  </div>
</template>

<script>
const columns = [
  {
    name: "calories",
    align: "left",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "Calories",
    field: "calories",
    sortable: true,
  },
];
const overdue_principals_days_columns = [
  {
    name: "calories",
    align: "left",
		label:"overdue_principals_days",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },

];
const elektr_columns = [
  {
    name: "calories",
    align: "left",
    label: "Год",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "месяц",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: "текущий долг",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "непогашенный долг",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "пересмотренный долг",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "штрафы",
    field: (row) => row.sodium,
  },
];
const inps_columns = [
  {
    name: "calories",
    align: "left",
    label: "ORG_INN",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "INCOME_SUMMA",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " NUM",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "PERIOD",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "ORGNAME",
    field: (row) => row.protein,
  },

];
const contingent_liability_columns = [
  {
    name: "calories",
    align: "left",
    label: "amount",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "subject_type",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " overdue_debt_sum",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "org",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "contract_id",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "overdue_debt_sum_change",
    field: (row) => row.branch,
  },
  {
    name: "calories",
    align: "left",
    label: "contract_status",
    field: (row) => row.percent,
  },
  {
    name: "calories",
    align: "left",
    label: "branch",
    field: (row) => row.amount_change,
  },
   {
    name: "calories",
    align: "left",
    label: "amount_change",
    field: (row) => row.contract_end_date,
  },
  {
    name: "calories",
    align: "left",
    label: "percent",
    field: (row) => row.max_current_overdue,
  },
  {
    name: "calories",
    align: "left",
    label: "contract_end_date",
    field: (row) => row.contract_date,
  },
  {
    name: "calories",
    align: "left",
    label: "max_current_overdue",
    field: (row) => row.total_debt_sum,
  },
  {
    name: "calories",
    align: "left",
    label: "contract_date",
    field: (row) => row.currency,
  },
  {
    name: "calories",
    align: "left",
    label: "total_debt_sum",
    field: (row) => row.total_debt_sum_change,
  },
   {
    name: "calories",
    align: "left",
    label: "currency",
    field: (row) => row.percent_change,
  },
  {
    name: "calories",
    align: "left",
    label: "total_debt_sum_change",
    field: (row) => row.amount,
  },
  {
    name: "calories",
    align: "left",
    label: "percent_change",
    field: (row) => row.subject_type,
  },

];
const credit_request_columns = [
  {
    name: "calories",
    align: "left",
    label: "org",
    field: (row) => row.calories,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "user_id",
    field: (row) => row.name,
  },
  {
    name: "calories",
    align: "left",
    label: " claim_id",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "report_type",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "consent_date",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "demand_date_time",
    field: (row) => row.branch,
  },
  {
    name: "calories",
    align: "left",
    label: "branch",
    field: (row) => row.percent,
  },
  {
    name: "calories",
    align: "left",
    label: "consent_id",
    field: (row) => row.amount_change,
  },
];
const blacklist_info_columns = [
  {
    name: "calories",
    align: "left",
    label: "claim_id",
    field: (row) => row.calories,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "exclusion_date",
    field: (row) => row.name,
  },
  {
    name: "calories",
    align: "left",
    label: " org_name",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "inclusion_date",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "claim_date",
    field: (row) => row.protein,
  },
];
const subscription_columns = [
  {
    name: "calories",
    align: "left",
    label: "org",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "user_id",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " claim_id",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "subscription_period",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "consent_date",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "branch",
    field: (row) => row.branch,
  },
  {
    name: "calories",
    align: "left",
    label: "consent_id",
    field: (row) => row.percent,
  },



];
const claim_wo_contract_columns = [
  {
    name: "calories",
    align: "left",
    label: "rejection_date",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "summa",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " org",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "claim_id",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "rejection_reason",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "currency",
    field: (row) => row.branch,
  },
  {
    name: "calories",
    align: "left",
    label: "branch",
    field: (row) => row.percent,
  },
	 {
    name: "calories",
    align: "left",
    label: "claim_date",
    field: (row) => row.claim_date,
  },



];
const claim_wo_contractsInfo_columns = [
  {
    name: "calories",
    align: "left",
    label: "RejectionDate",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "Summa",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " Org",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "ClaimId",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "RejectionReason",
    field: (row) => row.protein,
  },
  {
    name: "calories",
    align: "left",
    label: "Currency",
    field: (row) => row.branch,
  },
  {
    name: "calories",
    align: "left",
    label: "Branch",
    field: (row) => row.percent,
  },
	 {
    name: "calories",
    align: "left",
    label: "Branch",
    field: (row) => row.claim_date,
  },



];
const get_columns = [
  {
    name: "calories",
    align: "left",
    label: "scoring_category_id",
    field: (row) => row.name,
    format: (val) => `${val}`,
  },
  {
    name: "calories",
    align: "left",
    label: "scoring_category_name",
    field: (row) => row.calories,
  },
  {
    name: "calories",
    align: "left",
    label: " scoring_category_value_id",
    field: (row) => row.fat,
  },
  {
    name: "calories",
    align: "left",
    label: "scoring_category_value_name",
    field: (row) => row.carbs,
  },
  {
    name: "calories",
    align: "left",
    label: "score",
    field: (row) => row.protein,
  },
];
const user_data = [
  {
    name: "first_name",
    calories: "first_name",
  },
  {
    name: "last_name",
    calories: " last_name",
  },
  {
    name: "sur_name",
    calories: "sur_name",
  },
  {
    name: "inn",
    calories: "inn",
  },
  {
    name: "pinfl",
    calories: "pinfl",
  },
  {
    name: "bio_passport_serial",
    calories: "bio_passport_serial",
  },
  {
    name: "bio_passport_number",
    calories: "bio_passport_number",
  },
  {
    name: "bio_passport_issue_date",
    calories: "bio_passport_issue_date",
  },
  {
    name: "bio_passport_expire_date",
    calories: "bio_passport_expire_date",
  },
  {
    name: "bio_passport_whom_given",
    calories: "bio_passport_whom_given",
  },
  {
    name: "birht_date",
    calories: " birht_date",
  },
  {
    name: "address",
    calories: " address",
  },
];
const ruyxat = [
  {
    name: "id",
    calories: "id",
  },
  {
    name: "credit_id",
    calories: "credit_id",
  },
  {
    name: "amount",
    calories: "amount",
  },
  {
    name: "duration",
    calories: "duration",
  },
  {
    name: "name",
    calories: "name",
  },
  {
    name: "passport",
    calories: "passport",
  },
  {
    name: "tin",
    calories: "tin",
  },
  {
    name: "credit_status",
    calories: "credit_status",
  },
  {
    name: "contract_date",
    calories: "contract_date",
  },
  {
    name: "overdue_days",
    calories: "overdue_days",
  },
  {
    name: "merchant_id",
    calories: "merchant_id",
  },
  {
    name: "merchant_name",
    calories: "merchant_name",
  },
];
const katm_passport = [
  {
    name: "Document",
    calories: "Document",
  },
  {
    name: "SurnameLatin",
    calories: "SurnameLatin",
  },
  {
    name: "NameLatin",
    calories: "NameLatin",
  },
  {
    name: "MiddleNameLatin",
    calories: "MiddleNameLatin",
  },
  {
    name: "SurnameEng",
    calories: "SurnameEng",
  },
  {
    name: "NameEng",
    calories: "NameEng",
  },
  {
    name: "BirthDate",
    calories: "BirthDate",
  },
  {
    name: "BirthPlaceId",
    calories: "BirthPlaceId",
  },
  {
    name: "BirthCountry",
    calories: "BirthCountry",
  },
  {
    name: "BirthCountryId",
    calories: "BirthCountryId",
  },
  {
    name: "LiveStatus",
    calories: "LiveStatus",
  },
  {
    name: "Nationality",
    calories: "Nationality",
  },
  {
    name: "NationalityId",
    calories: "NationalityId",
  },
  {
    name: "Citizenship",
    calories: "Citizenship",
  },
  {
    name: "CitizenshipId",
    calories: "CitizenshipId",
  },
  {
    name: "Sex",
    calories: "Sex",
  },
  {
    name: "DocGivePlace",
    calories: "DocGivePlace",
  },
  {
    name: "DocGivePlaceId",
    calories: "DocGivePlaceId",
  },
  {
    name: "DateBeginDocument",
    calories: "DateBeginDocument",
  },
  {
    name: "DateEndDocument",
    calories: "DateEndDocument",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const address_res = [
  {
    name: "Country",
    calories: "Country",
  },
  {
    name: "Region",
    calories: "Region",
  },
  {
    name: "District",
    calories: "District",
  },
  {
    name: "Address",
    calories: "Address",
  },
  {
    name: "RegDate",
    calories: "RegDate",
  },
  {
    name: "Cadastre",
    calories: "Cadastre",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const address_reg = [
  {
    name: "Country",
    calories: "Country",
  },
  {
    name: "Region",
    calories: "Region",
  },
  {
    name: "District",
    calories: "District",
  },
  {
    name: "Address",
    calories: "Address",
  },
  {
    name: "RegDate",
    calories: "RegDate",
  },
  {
    name: "Cadastre",
    calories: "Cadastre",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },

  {
    Result: "05000",
    ResultMessage: "Successful",
  },
];
const address = [
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const elektr = [
  {
    name: "state",
    calories: "state",
  },
  {
    name: "message",
    calories: "message",
  },
];
const elektr1 = [
  {
    name: "name",
    calories: "name",
  },
];
const elektr2 = [
  {
    calories: "mar",
    name: "2021",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "apr",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "may",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "jun",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "jul",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
    name: "",
  },
  {
    calories: "aug",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "sep",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "oct",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "nov",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
  {
    calories: "dec",
    name: "",
    fat: "0",
    carbs: "23",
    protein: "6.0",
    sodium: "337",
  },
];
const elektr2else = [
  {
    calories: "",
    name: "2021",
    fat: "",
    carbs: "",
    protein: "",
    sodium: "",
  },
];
const elektrelse = [
  {
    name: "state",
    calories: "state",
  },
  {
    name: "message",
    calories: "message",
  },
];
const elektr1else = [
  {
    name: "name",
    calories: "name",
  },
];
const water = [
  {
    name: "ResultCode",
    calories: "ResultCode",
  },
  {
    name: "result_message",
    calories: " result_message",
  },
  {
    name: "abonentfio",
    calories: "abonentfio",
  },
  {
    name: "licshet",
    calories: "licshet",
  },
  {
    name: "passport_number",
    calories: "passport_number",
  },
  {
    name: "pinfl",
    calories: "pinfl",
  },
  {
    name: "kadastrnumber",
    calories: "kadastrnumber",
  },
  {
    name: "phone",
    calories: "phone",
  },
  {
    name: "regions_name",
    calories: "regions_name",
  },
  {
    name: "areas_name",
    calories: "areas_name",
  },
  {
    name: "mahalla_name",
    calories: " mahalla_name",
  },
  {
    name: "streets_name",
    calories: " streets_name",
  },
  {
    name: "address",
    calories: " address",
  },
  {
    name: "company_name",
    calories: " company_name",
  },
  {
    name: "contract_date",
    calories: " contract_date",
  },
  {
    name: "current_liver_count",
    calories: " current_liver_count",
  },
  {
    name: "fmal_saldo",
    calories: " fmal_saldo",
  },
];
const mib = [
  {
    name: "AllDebtSum",
    calories: "AllDebtSum",
  },
  {
    name: "Debts",
    calories: " Debts",
  },
  {
    name: "PassportNumber",
    calories: "PassportNumber",
  },
  {
    name: "PassportSn",
    calories: "PassportSn",
  },
  {
    name: "ReviewDate",
    calories: "ReviewDate",
  },
  {
    name: "Result",
    calories: "Result",
  },
  {
    name: "ResultMessage",
    calories: "ResultMessage",
  },
];
const inps = [
  {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  }, {
   calories: "ORG_INN",
    name: "INCOME_SUMMA",
    fat: "NUM",
    carbs: "PERIOD",
    protein: "ORGNAME",

  },
];
const incomes_period = [
  {
   calories: "incomes_period_begin",
    name: "incomes_period_begin",
  },  {
   calories: "incomes_period_end",
    name: "incomes_period_end",
  },  {
   calories: "incomes_all_summa",
    name: "incomes_all_summa",
  },
];
const sysinfo = [
  {
   calories: "Date",
    name: "Date",
  },
   {
   calories: "Bank",
    name: "Bank",
  },
   {
   calories: "id_demand",
    name: "id_demand",
  },
  {
   calories: "user_id",
    name: "user_id",
  },
  {
   calories: "claim_id",
    name: "claim_id",
  },
  {
   calories: "report_name",
    name: "report_name",
  }, {
   calories: "Declaration",
    name: "Declaration",
  }, {
   calories: "Branch",
    name: "Branch",
  }, {
   calories: "claim_date",
    name: "claim_date",
  }, {
   calories: "report_code",
    name: "report_code",
  },
];
const presence_report = [
   {
   calories: "presence_report",
    name: "presence_report",
  },
]
const client = [
   {
   calories: "pinfl",
    name: "pinfl",
  },
  {
   calories: "address",
    name: "address",
  },
  {
   calories: "document_number",
    name: "document_number",
  },
  {
   calories: "gender",
    name: "gender",
  },
  {
   calories: "document_type_id",
    name: "document_type_id",
  },
  {
   calories: "birth_date",
    name: "birth_date",
  },
  {
   calories: "name",
    name: "name",
  },
  {
   calories: "inn",
    name: "inn",
  },
  {
   calories: "document_date",
    name: "document_date",
  },
  {
   calories: "resident",
    name: "resident",
  },
  {
   calories: "document_type",
    name: "document_type",
  },
  {
   calories: "document_serial",
    name: "document_serial",
  },
]
const notification = [
   {
   calories: "Notification",
    name: "Notification",
  },
]
const contingent_liability = [
  {
   calories: "",
    name: "",
    fat: "",
    carbs: "",
    protein: "",
    branch:"",
    percent:"",
     amount_change: "",
    contract_end_date: "",
    max_current_overdue: "",
    contract_date: "",
    total_debt_sum: "",
    currency:"",
    total_debt_sum_change:"",
    percent_change: "",
    amount: "",
    subject_type:"",


  },
];
const overview = [
   {
   calories: "contingent_liabilities_qty",
    name: "contingent_liabilities_qty",
  },
  {
   calories: "max_overdue_principal_sum",
    name: "max_overdue_principal_sum",
  },
  {
   calories: "max_uninter_overdue_percent_days",
    name: "max_uninter_overdue_percent_days",
  },
  {
   calories: "max_overdue_principal_days",
    name: "max_overdue_principal_days",
  },
  {
   calories: "total_overdue_percent_sum",
    name: "total_overdue_percent_sum",
  },
  {
   calories: "credit_request_qty",
    name: "credit_request_qty",
  },
  {
   calories: "claims_qty",
    name: "claims_qty",
  },
   {
   calories: "average_monthly_payment",
    name: "average_monthly_payment",
  },
    {
   calories: "subscriptions_qty",
    name: "subscriptions_qty",
  },
   {
   calories: "contracts_qty",
    name: "contracts_qty",
  },
   {
   calories: "overdue_principal_qty",
    name: "overdue_principal_qty",
  },
]
const subscription = [
  {
   calories: "",
    name: "",
    fat: "",
    carbs: "",
    protein: "",
    branch:"",
    percent:"",
  },
];
const scorring = [
   {
   calories: "scoring_version",
    name: "scoring_version",
  },
  {
   calories: "scoring_grade",
    name: "scoring_grade",
  },
  {
   calories: "scoring_class",
    name: "scoring_class",
  },
  {
   calories: "scoring_level",
    name: "scoring_level",
  },
]
const sysinfos = [
   {
   calories: "demand_id",
    name: "demand_id",
  },
  {
   calories: "notes",
    name: "notes",
  },
  {
   calories: "org",
    name: "org",
  },
  {
   calories: "user_id",
    name: "user_id",
  },
  {
   calories: "claim_id",
    name: "claim_id",
  },
  {
   calories: "report_type",
    name: "report_type",
  },
  {
   calories: "consent_date",
    name: "consent_date",
  },
  {
   calories: "report_name",
    name: "report_name",
  },
  {
   calories: "demand_date_time",
    name: "demand_date_time",
  },
  {
   calories: "branch",
    name: "branch",
  },
  {
   calories: "consent_id",
    name: "consent_id",
  },
  {
   calories: "claim_date",
    name: "claim_date",
  },
]
const credit_request = [
  {
   calories: "org",
    name: "user_id",
    fat: "claim_id",
    carbs: "report_type",
    protein: "consent_date",
    branch:"demand_date_time",
    percent:"branch",
    amount_change:"consent_id",
  },
];
const clients = [
   {
   calories: "pinfl",
    name: "pinfl",
  },
  {
   calories: "live_address",
    name: "live_address",
  },
  {
   calories: "registration_region",
    name: "registration_region",
  },
  {
   calories: "gender",
    name: "gender",
  },
  {
   calories: "registration_district",
    name: "registration_district",
  },
  {
   calories: "birth_date",
    name: "birth_date",
  },
  {
   calories: "inn",
    name: "inn",
  },
  {
   calories: "client_type",
    name: "client_type",
  },
  {
   calories: "founders",
    name: "founders",
  },
  {
   calories: "oked",
    name: "oked",
  },
  {
   calories: "email_change",
    name: "email_change",
  },
  {
   calories: "juridical_status",
    name: "juridical_status",
  },
  {
   calories: "name",
    name: "name",
  },
  {
   calories: "live_address_change",
    name: "live_address_change",
  },
  {
   calories: "email",
    name: "email",
  },
   {
   calories: "registration_address_change",
    name: "registration_address_change",
  },
]
const blacklist_info = [
  {
   calories: "",
    name: "",
    fat: "",
    carbs: "",
    protein: "",
    branch:"",
    percent:"",
    amount_change:"",
  },
];
const open_contracts = [
   {
   calories: "open_contracts",
    name: "open_contracts",
  },
]
const claim_wo_contract = [
  {
   calories: "rejection_date",
    name: "summa",
    fat: "org",
    carbs: "claim_id",
    protein: "rejection_reason",
    branch:"currency",
    percent:"branch",
    claim_date:"claim_date",
  },
];
const contracts = [
   {
   calories: "contracts",
    name: "contracts",
  },
]
const credit_requests = [
   {
   calories: "credit_requests",
    name: "credit_requests",
  },
]
const send = [
   {
   calories: "ClientId",
    name: "ClientId",
  },
	{
   calories: "IncomesSumma",
    name: "IncomesSumma",
  },
	{
   calories: "MonthlyAveragePayment",
    name: "MonthlyAveragePayment",
  },
	{
   calories: "Age",
    name: "Age",
  },
	{
   calories: "Period",
    name: "Period",
  },
	{
   calories: "Sex",
    name: "Sex",
  },
	{
   calories: "AllDebtSum",
    name: "AllDebtSum",
  },
	{
   calories: "Citizenship",
    name: "Citizenship",
  },
	{
   calories: "OrganizationAddress",
    name: "OrganizationAddress",
  },
	{
   calories: "ClientResidenceAddress",
    name: "ClientResidenceAddress",
  },
	{
   calories: "ContingentLiabilitiesQty",
    name: "ContingentLiabilitiesQty",
  },
]
const overdue_principals_days = [
   {

    name: "overdue_principals_days",
  },
	{

    name: "overdue_principals_days",
  },
	{

    name: "overdue_principals_days",
  },
	{

    name: "overdue_principals_days",
  },
	{
    name: "overdue_principals_days",
  },

]
const claim_wo_contracts_info = [
  {
   calories: "rejection_date",
    name: "summa",
    fat: "org",
    carbs: "claim_id",
    protein: "rejection_reason",
    branch:"currency",
    percent:"branch",
    claim_date:"claim_date",
  },
];
const get = [
  {
   calories: "scoring_category_id",
    name: "scoring_category_name",
    fat: "scoring_category_value_id",
    carbs: "scoring_category_value_name",
    protein: "score",
  },
];
export default {
  setup() {
    return {
      columns,
      contingent_liability_columns,
      credit_request_columns,
      subscription_columns,
		  overdue_principals_days_columns,
			get_columns,
      blacklist_info_columns,
			claim_wo_contractsInfo_columns,
			claim_wo_contract_columns,
      inps_columns,
      user_data,
      ruyxat,
      katm_passport,
      address_res,
      address_reg,
      address,
      elektr,
      elektr1,
      elektr_columns,
      elektr2,
      elektrelse,
      elektr1else,
      elektr2else,
      water,
      mib,
      inps,
      incomes_period,
      sysinfo,
      presence_report,
      client,
      notification,
      contingent_liability,
      overview,
      subscription,
      scorring,
      sysinfos,
      credit_request,
      clients,
      blacklist_info,
			open_contracts,
			claim_wo_contract,
			contracts,
			credit_requests,
			send,
			overdue_principals_days,
			claim_wo_contracts_info,
			get
    };
  },
};
</script>
<style lang="scss">
.q-table {
  th {
    border: 0.5px solid black;
  }
  tbody {
    tr {
      td {
        border: 0.5px solid black;
      }
    }
  }
}
</style>

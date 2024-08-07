local storgar can't hold the data other than string
wo that we hav to convert json to string
// to get the previouse enter values. and to convert string of obj
        const fetchcovidVaccinationDetails=JSON.parse(localStorage.getItem("covidVaccinationDetails"))||[];
//        // api call if using api
        // const result=fetch("https://dummy.restapiexample.com/api/v1/create",{method:"POST", body:JSON.stringify(obj)}).then((item)=>item.json()).then((value)=>console.log(value)).catch((error)=>console.log(error))

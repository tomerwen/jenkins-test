pipeline{
    agent any
    parametes {
        booleanParam(defaultValue: false, description:"Enable service?" , name:myBoolean )
    }
    stages{
        Stage("Demo"){
            steps{
                echo "booleanParam is set to: ${params.myBoolean}"
            }
        }
    }
}
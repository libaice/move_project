1. docker config and supra cli
   * alias supra="docker exec -it supra_cli /supra/supra"

2. move contract and contract test

3. contract interaction command     
    * supra move tool publish --package-dir /supra/configs/move_workspace/<PROJECT_NAME> --profile <YOUR_PROFILE> --url <RPC_URL>
    * supra move tool view --function-id '<exampleAddress>::transfer::view_balance' --args address:<ADDRESS_TO_CHECK> --url <RPC_URL>
    * supra move tool run --function-id '<exampleAddress>::transfer::two_by_two' --args u64:<AMOUNT> address:<FIRST_ADR> address:<SECOND_ADR> --url <RPC_URL>
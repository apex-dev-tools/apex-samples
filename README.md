# Apex Test Samples

This directory contains a number of test samples as git modules for regression testing.

If you want to test against these locally run:

    git submodule update --init

To update submodules to with latest remote changes:

    git submodule update --init --remote

To add a sample follow the pattern below. In some cases a custom sfdx-project.json file is needed to load dependencies. To accommodate that the submodules are placed in sub-directory and the custom sfdx-project.json can then be checked into the parent, e.g. fflib-apex-common-samplecode/sfdx-project.json.  

    git submodule add https://github.com/se6wagner/TriggerX.git TriggerX/TriggerX
    git submodule add https://github.com/4an70m/apex-query-builder.git apex-query-builder/apex-query-builder
    git submodule add https://github.com/ccoenraets/salesforce-bot-toolkit.git salesforce-bot-toolkit/salesforce-bot-toolkit
    git submodule add https://github.com/developerforce/SalesforceDurableStreamingDemo.git SalesforceDurableStreamingDemo/SalesforceDurableStreamingDemo
    git submodule add https://github.com/bobalicious/amoss.git amoss/amoss
    git submodule add https://github.com/jongpie/SimpleLightningComponents.git SimpleLightningComponents/SimpleLightningComponents
    git submodule add https://github.com/LawrenceLoz/FormulaShare-DX.git FormulaShare-DX/FormulaShare-DX
    git submodule add https://github.com/benedwards44/Apex-for-Xero.git Apex-for-Xero/Apex-for-Xero
    git submodule add https://github.com/sendgrid/sendgrid-apex.git sendgrid-apex/sendgrid-apex
    git submodule add https://github.com/SalesforceLabs/FindNearby.git FindNearby/FindNearby
    git submodule add https://github.com/codefriar/promiseV3.git promiseV3/promiseV3
    git submodule add https://github.com/amorek/Apex-Opensource-Library.git Apex-Opensource-Library/Apex-Opensource-Library
    git submodule add https://github.com/JitendraZaa/SFDCRules.git SFDCRules/SFDCRules
    git submodule add https://github.com/davidsbond/forcelog.git forcelog/forcelog
    git submodule add https://github.com/skolakan/Apex-XML-Serializer.git Apex-XML-Serializer/Apex-XML-Serializer
    git submodule add https://github.com/kyleschmid/ObjectMerge.git ObjectMerge/ObjectMerge
    git submodule add https://github.com/open-force/grid.git grid/grid
    git submodule add https://github.com/stomita/soql-secure.git soql-secure/soql-secure 
    git submodule add https://github.com/box/box-salesforce-sdk.git box-salesforce-sdk/box-salesforce-sdk
    git submodule add https://github.com/mailtoharshit/Angular.git Angular/Angular
    git submodule add https://github.com/ChrisAldridge/Lightweight-Trigger-Framework.git Lightweight-Trigger-Framework/Lightweight-Trigger-Framework
    git submodule add https://github.com/mattaddy/SObjectFabricator.git SObjectFabricator/SObjectFabricator
    git submodule add https://github.com/apexfarm/ApexTriggerHandler.git ApexTriggerHandler/ApexTriggerHandler
    git submodule add https://github.com/afawcett/forcedotcom-enterprise-architecture.git forcedotcom-enterprise-architecture/forcedotcom-enterprise-architecture
    git submodule add https://github.com/GSA/sf-sandbox-post-copy.git sf-sandbox-post-copy/sf-sandbox-post-copy
    git submodule add https://github.com/TehNrd/Multi-File-Uploader-Force.com.git Multi-File-Uploader-Force/Multi-File-Uploader-Force
    git submodule add https://github.com/Szandor72/logger.git logger/logger
    git submodule add https://github.com/afawcett/apex-sobjectdataloader.git apex-sobjectdataloader/apex-sobjectdataloader
    git submodule add https://github.com/jpmonette/q.git q/q
    git submodule add https://github.com/appero-com/MyTriggers.git MyTriggers/MyTriggers
    git submodule add https://github.com/financialforcedev/ForceDotComSprintWall.git ForceDotComSprintWall/ForceDotComSprintWall
    git submodule add https://github.com/callawaycloud/apex-rest-route.git apex-rest-route/apex-rest-route
    git submodule add https://github.com/afawcett/flowtoolbelt.git flowtoolbelt/flowtoolbelt
    git submodule add https://github.com/forcedotcom/user-access-visualization.git user-access-visualization/user-access-visualization
    git submodule add https://github.com/mshanemc/einstein-ai.git einstein-ai/einstein-ai
    git submodule add https://github.com/trailheadapps/purealoe-lwc.git purealoe-lwc/purealoe-lwc
    git submodule add https://github.com/danieljpeter/HyperBatch.git HyperBatch/HyperBatch
    git submodule add https://github.com/SFDO-Community-Sprints/Interactions-for-Student-Recruitment.git Interactions-for-Student-Recruitment/Interactions-for-Student-Recruitment
    git submodule add https://github.com/rsoesemann/sobject-work-queue.git sobject-work-queue/sobject-work-queue
    git submodule add https://github.com/financialforcedev/ffhttp-core.git ffhttp-core/ffhttp-core
    git submodule add https://github.com/developerforce/Force.com-Toolkit-for-Facebook.git Force.com-Toolkit-for-Facebook/Force.com-Toolkit-for-Facebook
    git submodule add https://github.com/jesperfj/sfdc-oauth-playground.git sfdc-oauth-playground/sfdc-oauth-playground
    git submodule add https://github.com/dhoechst/salesforce-limit-monitor.git salesforce-limit-monitor/salesforce-limit-monitor
    git submodule add https://github.com/scottbcovert/Centralized-Salesforce-Dev-Framework.git Centralized-Salesforce-Dev-Framework/Centralized-Salesforce-Dev-Framework
    git submodule add https://github.com/afawcett/eventlogging.git eventlogging/eventlogging
    git submodule add https://github.com/fostive/quiz-host-app.git quiz-host-app/quiz-host-app
    git submodule add https://github.com/douglascayers/sfdc-related-files-lightning.git sfdc-related-files-lightning/sfdc-related-files-lightning
    git submodule add https://github.com/TehNrd/sObject-Remote.git sObject-Remote/sObject-Remote
    git submodule add https://github.com/rsoesemann/apex-domainbuilder.git apex-domainbuilder/apex-domainbuilder
    git submodule add https://github.com/kevinohara80/Force.com-Helper-Classes.git Force.com-Helper-Classes/Force.com-Helper-Classes
    git submodule add https://github.com/bluewolf-beyond/selector.git selector/selector
    git submodule add https://github.com/PropicSignifi/R.apex.git R-apex/R-apex
    git submodule add https://github.com/j-fischer/rflib.git rflib/rflib
    git submodule add https://github.com/patronmanager/apex-dml-manager.git apex-dml-manager/apex-dml-manager
    git submodule add https://github.com/forcedotcom/ConnectApiHelper.git ConnectApiHelper/ConnectApiHelper    
    git submodule add https://github.com/douglascayers/sfdc-convert-attachments-to-chatter-files.git  sfdc-convert-attachments-to-chatter-files/sfdc-convert-attachments-to-chatter-files
    git submodule add https://github.com/Forceea/Forceea-data-factory.git Forceea-data-factory/Forceea-data-factory
    git submodule add https://github.com/apexfarm/ApexTestKit.git ApexTestKit/ApexTestKit
    git submodule add https://github.com/open-force/jsonparse.git jsonparse/jsonparse
    git submodule add https://github.com/SCWells72/sirono-common.git sirono-common/sirono-common
    git submodule add https://github.com/mitchspano/apex-trigger-actions-framework.git apex-trigger-actions-framework/apex-trigger-actions-framework
    git submodule add https://github.com/forcedotcom/force-dot-com-esapi.git esapi/esapi
    git submodule add https://github.com/apex-enterprise-patterns/at4dx.git at4dx/at4dx
    git submodule add https://github.com/SalesforceLabs/EnhancedLightningGrid.git EnhancedLightningGrid/EnhancedLightningGrid
    git submodule add https://github.com/mshanemc/processBuilderBlocks.git processBuilderBlocks/processBuilderBlocks
    git submodule add https://github.com/codefriar/promise.git promise/promise
    git submodule add https://github.com/SalesforceFoundation/Volunteers-for-Salesforce.git Volunteers-for-Salesforce/Volunteers-for-Salesforce
    git submodule add https://github.com/PropicSignifi/Query.apex.git Query.apex/Query.apex
    git submodule add https://github.com/rsoesemann/apex-unified-logging.git apex-unified-logging/apex-unified-logging
    git submodule add https://github.com/pdalcol/Zippex.git Zippex/Zippex
    git submodule add https://github.com/benahm/TestDataFactory.git TestDataFactory/TestDataFactory
    git submodule add https://github.com/apex-enterprise-patterns/fflib-apex-common-samplecode.git fflib-apex-common-samplecode/fflib-apex-common-samplecode
    git submodule add https://github.com/trailheadapps/automation-components.git automation-components/automation-components
    git submodule add https://github.com/apex-enterprise-patterns/force-di.git force-di/force-di
    git submodule add https://github.com/SalesforceFoundation/EDA.git EDA/EDA
    git submodule add https://github.com/ipavlic/apex-lambda.git apex-lambda/apex-lambda
    git submodule add https://github.com/douglascayers-org/sfdx-mass-action-scheduler.git sfdx-mass-action-scheduler/sfdx-mass-action-scheduler
    git submodule add https://github.com/trailheadapps/apex-recipes.git apex-recipes/apex-recipes
    git submodule add https://github.com/SalesforceFoundation/NPSP.git NPSP/NPSP
    git submodule add https://github.com/financialforcedev/apex-mdapi.git apex-mdapi/apex-mdapi
    git submodule add https://github.com/jamessimone/apex-rollup.git apex-rollup/apex-rollup
    git submodule add https://github.com/jongpie/NebulaLogger.git NebulaLogger/NebulaLogger
    git submodule add https://github.com/afawcett/apex-toolingapi.git apex-toolingapi/apex-toolingapi
    git submodule add https://github.com/mbotos/Automated-Testing-for-Force.com.git Automated-Testing-for-Force/Automated-Testing-for-Force
    git submodule add https://github.com/SalesforceFoundation/Cumulus.git Cumulus/Cumulus
    git submodule add https://github.com/forcedotcom/CustomMetadataLoader.git CustomMetadataLoader/CustomMetadataLoader
    git submodule add https://github.com/afawcett/declarative-lookup-rollup-summaries.git declarative-lookup-rollup-summaries/declarative-lookup-rollup-summaries
    git submodule add https://github.com/financialforcedev/df12-apex-enterprise-patterns.git df12-apex-enterprise-patterns/df12-apex-enterprise-patterns
    git submodule add https://github.com/financialforcedev/df12-deployment-tools.git df12-deployment-tools/df12-deployment-tools
    git submodule add https://github.com/dreamhouseapp/dreamhouse-sfdx.git dreamhouse-sfdx/dreamhouse-sfdx
    git submodule add https://github.com/financialforcedev/fflib-apex-common.git fflib-apex-common/fflib-apex-common
    git submodule add https://github.com/financialforcedev/fflib-apex-mocks.git fflib-apex-mocks/fflib-apex-mocks
    git submodule add https://github.com/SalesforceFoundation/HEDAP.git HEDAP/HEDAP
    git submodule add https://github.com/SalesforceLabs/Milestones-PM.git Milestones-PM/Milestones-PM
    git submodule add https://github.com/abhinavguptas/Salesforce-Lookup-Rollup-Summaries.git Salesforce-Lookup-Rollup-Summaries/Salesforce-Lookup-Rollup-Summaries
    git submodule add https://github.com/dhoechst/Salesforce-Test-Factory.git Salesforce-Test-Factory/Salesforce-Test-Factory
    git submodule add https://github.com/kevinohara80/sfdc-trigger-framework.git sfdc-trigger-framework/sfdc-trigger-framework
    git submodule add https://github.com/forcedotcom/sfdx-simple.git sfdx-simple/sfdx-simple
    git submodule add https://github.com/mbotos/SmartFactory-for-Force.com.git SmartFactory-for-Force/SmartFactory-for-Force
    git submodule add https://github.com/twilio/twilio-salesforce.git twilio-salesforce/twilio-salesforce
    git submodule add https://github.com/metadaddy/Visualforce-Multiselect-Picklist.git Visualforce-Multiselect-Picklist/Visualforce-Multiselect-Picklist
    git submodule add https://github.com/rsoesemann/visualforce-table-grid.git visualforce-table-grid/visualforce-table-grid
    git submodule add https://github.com/SalesforceFoundation/visualforce-typeahead.git visualforce-typeahead/visualforce-typeahead
    git submodule add https://github.com/SalesforceLabs/ActionPlansV4.git ActionPlansV4/ActionPlansV4
    git submodule add https://github.com/SalesforceLabs/survey-force.git survey-force/survey-force

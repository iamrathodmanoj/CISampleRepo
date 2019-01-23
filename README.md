# CISampleRepo
Build Status:

[![Build Status](https://dev.azure.com/iamrathodmanoj/iamrathodmanoj/_apis/build/status/iamrathodmanoj-ASP.NET%20Core%20(.NET%20Framework)-CI%20(1)?branchName=master)](https://dev.azure.com/iamrathodmanoj/iamrathodmanoj/_build/latest?definitionId=5?branchName=master)


# These owners will be the default owners for everything in
# the repo.
*                            @peopledoc/<project>-developers @peopledoc/<project>-po

# Dot-files should be handled by the lead dev (.gitignore and co)
.*                           @peopledoc/<project>-leaddev

# Frontend assets
*.js                         @peopledoc/tribe-js

# Template and assets
*.html *.css *.scss *.img    @peopledoc/tribe-ui

# Some module is quite complex, and shouldn't be touched without an expert
# chiming in
some_module/tricky_part/*.py @functional_expert1 @functional_expert2

# Schema and SQL migrations
*.sql *-ddl.pg               @peopledoc/dba

# QA
/tests/end2end/              @peopledoc/set

# Copywriting
*.po                         @peopledoc/localization-manager

# Devsec
/ansible/credentials/        @peopledoc/devsecops

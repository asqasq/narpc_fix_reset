<!--
{% comment %}

Copyright (C) 2016-2018, IBM Corporation

Licensed to the Apache Software Foundation (ASF) under one or more
contributor license agreements.  See the NOTICE file distributed with
this work for additional information regarding copyright ownership.
The ASF licenses this file to You under the Apache License, Version 2.0
(the "License"); you may not use this file except in compliance with
the License.  You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
{% endcomment %}
-->

# narpc
Nio based RPC library


# This version vs. original version
The original and always up-to-date version can be found at https://github.com/zrlio/narpc. The quick fix
to the deadlock is pulled from https://github.com/PepperJo/narpc.git branch fix_reset and rebased
to the https://github.com/zrlio/narpc master branch.

I pushed the merged version to this repository to facilitate building Docker containers with the fix
as used in https://github.com/asqasq/serverless.


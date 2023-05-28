V1.2.0 (05/28/2023) Bugfix release
- Bugfix: Fix nuget download bug
- Updates
    - Support Dymamic LINQ 1.3.2
    - SelectMany Bugfix : https://github.com/zzzprojects/System.Linq.Dynamic.Core/issues/511

V1.1.0 (10/26/2021) Feature release
- Updates
    - Update to Dynamic LINQ 1.2.13
        - Updated environment variable ```Nuget: SystemLinqDynamicCore```
    - Optimise Join
- New actions
    - Intersect
    - Except
    - Union
    - Concat
    - Distinct
- Bugfix: $ operator cast to ```DataTable``` automatically.
- Bugfix: VBO can run in background mode

V1.0.1 (05/30/2021) Bugfix release
- Change return flag name in ...OrDefault actions

V1.0.0 (05/29/2021) Initial release
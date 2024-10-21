# ansible_user_module_test

A simple [molecule](https://ansible.readthedocs.io/projects/molecule/) role to check the behaviour of the [ansible.builtin.user](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/user_module.html) module.

# Version Info

```
molecule --version
molecule 24.9.0 using python 3.12
    ansible:2.17.4
    default:24.9.0 from molecule
    docker:2.1.0
```

# Running the tests

```bash
molecule test
```

# Sample Output

```
TASK [Test user 1] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser1",
        "delta": "0:00:00.001188",
        "end": "2024-10-21 09:47:08.402881",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:08.401693",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 1] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser1",
        "delta": "0:00:00.001231",
        "end": "2024-10-21 09:47:09.450756",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:09.449525",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 2] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser2",
        "delta": "0:00:00.001208",
        "end": "2024-10-21 09:47:10.530890",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:10.529682",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 3] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser3",
        "delta": "0:00:00.001302",
        "end": "2024-10-21 09:47:11.544883",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:11.543581",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 4] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser4",
        "delta": "0:00:00.001185",
        "end": "2024-10-21 09:47:12.590104",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:12.588919",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 5] *************************************************************
[WARNING]: The input password appears not to have been hashed. The 'password'
argument must be encrypted for this module to work properly.
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser5",
        "delta": "0:00:00.001237",
        "end": "2024-10-21 09:47:13.661298",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:13.660061",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 6] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser6",
        "delta": "0:00:00.001264",
        "end": "2024-10-21 09:47:14.663044",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:14.661780",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 99999\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 99999",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 7] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser7",
        "delta": "0:00:00.001182",
        "end": "2024-10-21 09:47:15.697268",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:15.696086",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: -1\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: -1",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 8] *************************************************************
ok: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser8",
        "delta": "0:00:00.001228",
        "end": "2024-10-21 09:47:16.741680",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:16.740452",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: -1\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: -1",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 9] *************************************************************
changed: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser9",
        "delta": "0:00:00.001234",
        "end": "2024-10-21 09:47:17.822784",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:17.821550",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: Oct 21, 2025\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 365\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: Oct 21, 2025",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 365",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 9] *************************************************************
changed: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser9",
        "delta": "0:00:00.001312",
        "end": "2024-10-21 09:47:18.856429",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:18.855117",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: Oct 21, 2025\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: 365\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: Oct 21, 2025",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: 365",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

TASK [Test user 9] *************************************************************
changed: [ubuntu]

TASK [shell] *******************************************************************
ok: [ubuntu]

TASK [debug] *******************************************************************
ok: [ubuntu] => {
    "user": {
        "changed": false,
        "cmd": "chage -l testuser9",
        "delta": "0:00:00.001352",
        "end": "2024-10-21 09:47:19.900291",
        "failed": false,
        "msg": "",
        "rc": 0,
        "start": "2024-10-21 09:47:19.898939",
        "stderr": "",
        "stderr_lines": [],
        "stdout": "Last password change\t\t\t\t\t: Oct 21, 2024\nPassword expires\t\t\t\t\t: never\nPassword inactive\t\t\t\t\t: never\nAccount expires\t\t\t\t\t\t: never\nMinimum number of days between password change\t\t: 0\nMaximum number of days between password change\t\t: -1\nNumber of days of warning before password expires\t: 7",
        "stdout_lines": [
            "Last password change\t\t\t\t\t: Oct 21, 2024",
            "Password expires\t\t\t\t\t: never",
            "Password inactive\t\t\t\t\t: never",
            "Account expires\t\t\t\t\t\t: never",
            "Minimum number of days between password change\t\t: 0",
            "Maximum number of days between password change\t\t: -1",
            "Number of days of warning before password expires\t: 7"
        ]
    }
}

PLAY RECAP *********************************************************************
ubuntu                     : ok=36   changed=3    unreachable=0    failed=0    skipped=0    rescued=0    ignored=0
```
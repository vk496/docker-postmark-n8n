{
    "name": "Postmark Inbound",
    "nodes": [
        {
            "parameters": {
                "httpMethod": "POST",
                "path": "postmark-inbound",
                "options": {}
            },
            "type": "n8n-nodes-base.webhook",
            "typeVersion": 2,
            "position": [
                -120,
                -80
            ],
            "id": "6b76148d-5dc0-4836-b472-94ac0a4bfee2",
            "name": "Postmark Inbound",
            "webhookId": "cf78c92a-95f1-4558-9c3d-d56267f2f660"
        },
        {
            "parameters": {
                "content": "## Event\n\nThe event will be sent to **https://test-server.loca.lt/webhook/postmark-inbound**\n\n```\n$ docker compose logs lt\n your url is: https://test-server.loca.lt\n```",
                "height": 480,
                "width": 680
            },
            "type": "n8n-nodes-base.stickyNote",
            "position": [
                -220,
                -340
            ],
            "typeVersion": 1,
            "id": "217590be-efb0-4338-b893-53f678125af9",
            "name": "Sticky Note"
        }
    ],
    "pinData": {
        "Postmark Inbound": [
            {
                "json": {
                    "headers": {
                        "x-forwarded-for": "18.217.206.57",
                        "x-forwarded-port": "443",
                        "host": "n8n",
                        "x-forwarded-proto": "https, https",
                        "content-length": "5481",
                        "content-type": "application/json",
                        "user-agent": "Postmark",
                        "accept": "application/json",
                        "x-forwarded-host": "test-server.loca.lt",
                        "connection": "keep-alive"
                    },
                    "params": {},
                    "query": {},
                    "body": {
                        "FromName": "Valentin Kivachuk",
                        "MessageStream": "inbound",
                        "From": "vk18496@gmail.com",
                        "FromFull": {
                            "Email": "vk18496@gmail.com",
                            "Name": "Valentin Kivachuk",
                            "MailboxHash": ""
                        },
                        "To": "f8d8d155731028dad1b8c9c7bbf1bf13@inbound.postmarkapp.com",
                        "ToFull": [
                            {
                                "Email": "f8d8d155731028dad1b8c9c7bbf1bf13@inbound.postmarkapp.com",
                                "Name": "",
                                "MailboxHash": ""
                            }
                        ],
                        "Cc": "",
                        "CcFull": [],
                        "Bcc": "",
                        "BccFull": [],
                        "OriginalRecipient": "f8d8d155731028dad1b8c9c7bbf1bf13@inbound.postmarkapp.com",
                        "Subject": "Hello!",
                        "MessageID": "0701c017-3fc3-45fd-a1a7-ef8a7e64617a",
                        "ReplyTo": "",
                        "MailboxHash": "",
                        "Date": "Sat, 24 May 2025 22:17:24 +0200",
                        "TextBody": "This is a test email\n",
                        "HtmlBody": "<div dir=\"ltr\">This is a test email</div>\n",
                        "StrippedTextReply": "",
                        "Tag": "",
                        "Headers": [
                            {
                                "Name": "Return-Path",
                                "Value": "<vk18496@gmail.com>"
                            },
                            {
                                "Name": "Received",
                                "Value": "by p-pm-inboundg01a-aws-useast1a.inbound.postmarkapp.com (Postfix, from userid 996)\tid 3C96F453B34; Sat, 24 May 2025 20:17:36 +0000 (UTC)"
                            },
                            {
                                "Name": "X-Spam-Checker-Version",
                                "Value": "SpamAssassin 3.4.0 (2014-02-07) on\tp-pm-inboundg01a-aws-useast1a"
                            },
                            {
                                "Name": "X-Spam-Status",
                                "Value": "No"
                            },
                            {
                                "Name": "X-Spam-Score",
                                "Value": "-0.1"
                            },
                            {
                                "Name": "X-Spam-Tests",
                                "Value": "DKIM_SIGNED,DKIM_VALID,DKIM_VALID_AU,FREEMAIL_FROM,HTML_MESSAGE,\tRCVD_IN_DNSWL_BLOCKED,RCVD_IN_MSPIKE_H2,RCVD_IN_VALIDITY_RPBL_BLOCKED,\tRCVD_IN_VALIDITY_SAFE_BLOCKED,RCVD_IN_ZEN_BLOCKED_OPENDNS,SPF_HELO_NONE,\tSPF_PASS"
                            },
                            {
                                "Name": "Received-SPF",
                                "Value": "pass (gmail.com ... _spf.google.com: Sender is authorized to use 'vk18496@gmail.com' in 'mfrom' identity (mechanism 'include:_netblocks.google.com' matched)) receiver=p-pm-inboundg01a-aws-useast1a; identity=mailfrom; envelope-from=\"vk18496@gmail.com\"; helo=mail-yb1-f177.google.com; client-ip=209.85.219.177"
                            },
                            {
                                "Name": "Received",
                                "Value": "from mail-yb1-f177.google.com (mail-yb1-f177.google.com [209.85.219.177])\t(using TLSv1.2 with cipher ECDHE-RSA-AES128-GCM-SHA256 (128/128 bits))\t(No client certificate requested)\tby p-pm-inboundg01a-aws-useast1a.inbound.postmarkapp.com (Postfix) with ESMTPS id D361F40502E\tfor <f8d8d155731028dad1b8c9c7bbf1bf13@inbound.postmarkapp.com>; Sat, 24 May 2025 20:17:35 +0000 (UTC)"
                            },
                            {
                                "Name": "Received",
                                "Value": "by mail-yb1-f177.google.com with SMTP id 3f1490d57ef6-e7da03bb0cdso118578276.3        for <f8d8d155731028dad1b8c9c7bbf1bf13@inbound.postmarkapp.com>; Sat, 24 May 2025 13:17:35 -0700 (PDT)"
                            },
                            {
                                "Name": "DKIM-Signature",
                                "Value": "v=1; a=rsa-sha256; c=relaxed/relaxed;        d=gmail.com; s=20230601; t=1748117855; x=1748722655; darn=inbound.postmarkapp.com;        h=to:subject:message-id:date:from:mime-version:from:to:cc:subject         :date:message-id:reply-to;        bh=s3dPmGJaPONzYT2L+qCO8byw8T0yX1Jzab0n4G5AoTQ=;        b=F/JXQUwueLs+XJ0BYFTfSfItSe5jSW7CjCFEiOfmOoW//97QJra4Gw6sC6tP6Xxqd9         IXmauUcvPpDBnfTE3DX8Cw6qUaQDlCb47m4cxbKOBLkrW9y0KDoQ4g/iWJhSPGFF0PHo         QUiclqaVasn3u0ix24fT2zH84M6d0ASN51MxiYTUD0oxtmNEzS4xejX7i4Tt4fZ++4Xm         cmwSyu3fximm5OFqmlcCOeOKTolIsZPCnGKiPYqJ2Y6gujBDU2/JcpT5CDiMxniglNs0         QQNlO63kFbcYyV4BqTkgmKCPvedUu3smDjJDYjqP4ynTDmMGfog0O4kDOPktoJqhpV/A         h9iw=="
                            },
                            {
                                "Name": "X-Google-DKIM-Signature",
                                "Value": "v=1; a=rsa-sha256; c=relaxed/relaxed;        d=1e100.net; s=20230601; t=1748117855; x=1748722655;        h=to:subject:message-id:date:from:mime-version:x-gm-message-state         :from:to:cc:subject:date:message-id:reply-to;        bh=s3dPmGJaPONzYT2L+qCO8byw8T0yX1Jzab0n4G5AoTQ=;        b=berpcBf7N0ZXS4yQfUI6b2T6vU7jMCRWW3OJyTCNehktLoYn/+XMOmdANf3ZDy/DSz         36akcPr9lv0qojJ9YRHdh4Tfl0DNzHbvTArZWLcurt35XOlPZohPRpd3GUgYJZJ12ljB         F0TRsQ8dEH/4YNN8q8kFvjGwbmVQASHYc+ly59rNek4JsFxzcQfFTreW6oWdE27iR/ex         Lq32y86XP8jbscOAK2Ndx/lyTNDG+MJajULPcGq2tpRF3StnYDwcYX5P+seipqz3+XEe         HWhEvVr9mimy7UtcGeBY5+bdjIJCA23uHENwPQN/343VLzgc4tH2IlipYaREuPSnHq83         4Exw=="
                            },
                            {
                                "Name": "X-Gm-Message-State",
                                "Value": "AOJu0YxMrHJokSr1fb9t1CbAAOZgX5WmC+22DZ3zYsnunLr2KAivdN/2\tpBhQY7AKSl0Xp8i/UynDG3q35XMVNCveQIJ1OdtbinVhBeqeEsQKxb8HGM50vanfueYPkgcMXF3\td4zqyMBTENmRfutA4PA0Vjr+UIGdCNFEgQQ=="
                            },
                            {
                                "Name": "X-Gm-Gg",
                                "Value": "ASbGncvllYHt5dBCEMQ3jRjTUwBeWthoRaH+VBuE6ygAxH+t/VuYRYhaOW9ToP/1KBX\t63+Gbw9gI/n3t6Tfl7DKYQbb+W4LJ+JaT1BJSG6Thws0FZD18vnhTJZNHcL6lSO14EvdhgpVbrU\t4AWptzmH4/yA5EbCc1656chhvdTRKuuuXA+B3e9zND/cQ7NSMpggE="
                            },
                            {
                                "Name": "X-Google-Smtp-Source",
                                "Value": "AGHT+IE8yDpJyDl9VkHnNeTGL02LP8Nmt9/e0RmpgfKveGV5HPxV6I+3RNbGz6x9tZosmkoHSIlp+gcnAFAet8Uwtxs="
                            },
                            {
                                "Name": "X-Received",
                                "Value": "by 2002:a05:6902:1082:b0:e7d:62d3:9fe2 with SMTP id 3f1490d57ef6-e7d919e937amr3686104276.29.1748117855390; Sat, 24 May 2025 13:17:35 -0700 (PDT)"
                            },
                            {
                                "Name": "MIME-Version",
                                "Value": "1.0"
                            },
                            {
                                "Name": "X-Gm-Features",
                                "Value": "AX0GCFsxcLb7diX_95ipSOvZN6MHLgm0d00o0Zgm9LjrWhUkwpYpG_DZUjS4XzQ"
                            },
                            {
                                "Name": "Message-ID",
                                "Value": "<CAFhvtDAAogDb=s1_d08ttuAN9pZrYYBarFfDxzQjiH6D91ra3A@mail.gmail.com>"
                            }
                        ],
                        "Attachments": []
                    },
                    "webhookUrl": "http://localhost:5678/webhook/postmark-inbound",
                    "executionMode": "production"
                }
            }
        ]
    },
    "connections": {
        "Postmark Inbound": {
            "main": [
                []
            ]
        }
    },
    "active": true,
    "settings": {
        "executionOrder": "v1"
    },
    "versionId": "dd7e9c3f-a704-45a4-87ba-609cd85a084d",
    "meta": {
        "templateCredsSetupCompleted": true,
        "instanceId": "a27fce593a3ba2a3e57fb140952cb0e68a10b0851aef301102807c84fd72263d"
    },
    "id": "9gs351NIzAzBH7cK",
    "tags": []
}

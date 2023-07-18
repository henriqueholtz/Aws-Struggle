Security Group acts as a firewall at the instance level whereas Network Access Control List (Network ACL) acts as a firewall at the subnet level

<details>
<summary>Image-Example</summary>

![img](https://images.squarespace-cdn.com/content/v1/5ff2206c3fe4fe33db8ecbb4/1613432262545-3GFTJ1L5E97CQEGYN5RC/AmazonVPC.png)

</details>

- SG is statefull (verify once the rules inbound or outbound);
- NACL is stateless (verify rules when inbound **and** outbound);

---

- SG Only have allow rules;
- NACL have allow and deny rules;
